# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/osx'

begin
  require 'bundler'
  Bundler.setup
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  app.name = 'Limer'
  app.version = '0.0.1'
  app.short_version = '1'
  app.copyright = 'Copyright © 2013 Mohawk Apps, LLC. All rights reserved.'
  app.sdk_version = "10.8"
  app.deployment_target = "10.8"
	app.identifier = 'com.mohawkapps.limer'
	app.icon = 'Limer.icns'
	app.frameworks += %w(ScriptingBridge)
  app.category = 'developer-tools'
end
