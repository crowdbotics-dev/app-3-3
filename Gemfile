source "https://rubygems.org"

gem "fastlane", "~>2.205.0"
gem "httparty"
gem "cocoapods"
gem "xcode-install"

android_plugins_path = File.join(
  File.dirname(__FILE__), 'android', 'fastlane', 'Pluginfile'
)
eval_gemfile(android_plugins_path) if File.exist?(android_plugins_path)
ios_plugins_path = File.join(
  File.dirname(__FILE__), 'ios', 'fastlane', 'Pluginfile'
)
eval_gemfile(ios_plugins_path) if File.exist?(ios_plugins_path)
