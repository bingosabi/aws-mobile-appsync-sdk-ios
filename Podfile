platform :ios, "9.0"

use_frameworks!
inhibit_all_warnings!

AWS_SDK_VERSION = "2.15.0"

target "AWSAppSync" do
  pod "AWSCore", :path => '../aws-sdk-ios'
  pod "SQLite.swift", "~> 0.12.2"
  pod "ReachabilitySwift", "~> 5.0.0"
  pod "AppSyncRealTimeClient", "~> 1.4"

  pod "SwiftLint"
end

target "AWSAppSyncTestCommon" do
  pod "AWSS3", :path => '../aws-sdk-ios'
  pod "ReachabilitySwift", "~> 5.0.0"
  # We directly access a database connection to verify certain initialization
  # setups
  pod "SQLite.swift", "~> 0.12.2"
  pod "AppSyncRealTimeClient", "~> 1.4"
end

target "AWSAppSyncTestApp" do
  pod "AWSS3", :path => '../aws-sdk-ios'
  pod "AWSMobileClient", :path => '../aws-sdk-ios'
end

target "AWSAppSyncTestHostApp" do
end

target "AWSAppSyncUnitTests" do
end

target "AWSAppSyncIntegrationTests" do
end

target "ApolloTests" do
  pod "AWSCore", :path => '../aws-sdk-ios'
end
