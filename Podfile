source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '8.0'

# flag makes all dependencies build as frameworks
use_frameworks!

abstract_target 'CobraBase' do

   # framework dependencies
   pod 'Swinject', '~> 1.1'

   target 'Medusa' do
   end

   # test specific dependencies
   target 'MedusaTests' do
      pod 'Quick', '~> 0.9.2'
      pod 'Nimble', '~> 4.0'
   end
end