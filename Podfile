# Uncomment the next line to define a global platform for your project
# platform :ios, '13.6'

target 'SocialApp' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

pod 'Bolts'
pod 'Firebase'
pod 'Firebase/Core'
pod 'Firebase/Messaging'
pod 'Firebase/Auth'

pod 'FacebookCore'
pod 'FacebookLogin'

#pod 'FacebookCore', :git => 'https://github.com/facebook/facebook-sdk-swift', :branch => 'master'

#pod 'FacebookLogin', :git => 'https://github.com/facebook/facebook-sdk-swift', :branch => 'master'

pod 'Google-Mobile-Ads-SDK', '~> 8.4.0'

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '5.0' 
    end
  end
end

end