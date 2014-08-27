# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'frameworks-extensions-test-app'

  app.sdk_version = '8.0'
  app.deployment_target = '8.0'

  app.target('extensions/today-extension', :extension)
  app.target('frameworks/framework-sample', :framework)
  # app.target('frameworks/framework-sample', :framework, load: false)

  app.codesign_certificate = "8HST5T82GA"
  app.provisioning_profile = "/Users/mark/src/Mark_Wildcard.mobileprovision"
end
