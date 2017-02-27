# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

platform :ios, '10.0'
use_frameworks!

target 'libSwift'

pod 'FacebookCore'
pod 'FacebookLogin'
pod 'FacebookShare'

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '3.0'
    end
  end
end
