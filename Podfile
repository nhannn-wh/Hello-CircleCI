# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Hello-CircleCI' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Hello-CircleCI

  pod 'YYWebImage', '1.0.5'
  pod 'IQKeyboardManagerSwift', '6.5.1'
  pod 'ReachabilitySwift', '4.3.1'
  pod 'SVProgressHUD', '2.2.5'
  pod 'MZFormSheetPresentationController'
  pod 'FacebookCore', '0.3.1'
  pod 'FacebookLogin', '0.3.1'
  pod 'TwitterKit'
  pod 'CRRefresh', '1.1.3'
  pod 'MTGeometry', '0.0.5'
  pod 'Firebase/Core'
  pod 'Firebase/Messaging'
  pod 'Firebase/Analytics'
  pod 'Fabric', '~> 1.9.0'
  pod 'Crashlytics', '~> 3.12.0'
  pod 'AppsFlyerFramework'
  pod 'FRHyperLabel', '1.0.4'
  pod 'Firebase/Performance'
  pod 'GoogleTagManager'
  pre_install do |installer|
      Pod::Installer::Xcode::TargetValidator.send(:define_method, :verify_no_static_framework_transitive_dependencies) {}
      
  end
end
