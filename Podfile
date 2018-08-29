use_frameworks!

workspace 'ResourceApp'
project 'ResourceApp/ResourceApp'

abstract_target 'Shared' do
  inhibit_all_warnings!

#  pod 'R.swift.Library', :git => 'git@github.com:mac-cain13/R.swift.Library.git' # for CI builds
  # pod 'R.swift.Library', :path => '../R.swift.Library' # for development
pod 'R.swift.Library', :git => 'https://github.com/yashbarotkunj/R.swift.Library.git', :commit => '98c6e32ebfa37bb858ab49b0e00f1ce742038fe6'
  target 'ResourceApp' do
    platform :ios, '9.0'

    pod 'SWRevealViewController'
  end
  target 'ResourceAppTests' do
    platform :ios, '9.0'

    pod 'SWRevealViewController'
  end
  target 'ResourceApp-tvOS' do
    platform :tvos, '9.0'
  end
end

