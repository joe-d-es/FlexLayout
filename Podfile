use_frameworks!
platform :ios, '8.0'

workspace 'FlexLayout.xcworkspace'

target 'FlexLayout' do
  project 'FlexLayout.xcodeproj'

  pod 'YogaKit'

  target 'FlexLayoutTests' do
    inherit! :search_paths
    pod 'Quick'
    pod 'Nimble', :inhibit_warnings => true
    pod 'YogaKit'
  end
end

target 'FlexLayoutSample' do
  project 'Example/FlexLayoutSample.xcodeproj'

  pod 'FlexLayout', :path => './'
  pod 'PinLayout'
  pod 'YogaKit'

  # Debug only
  pod 'SwiftLint'
end

