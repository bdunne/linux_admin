## v0.1.2
  - Bumping version to v0.1.2
  - add fstab module and specs
  - add service.restart, return 'self' in service methods
  - use custom runtime error subclass for command failures

## v0.1.1
  - Bumping version to 0.1.1
  - add special distro types (generic/test)
  - parse numeric partition sizes from parted output
  - tidy up new features, round out specs testing them
  - features to round out set
  - add system representation
  - add logical volume skeleton
  - add disk/partition representations & specs
  - start adding specs for services
  - add service representation
  - add distro representation
  - Improved test coverage of common
  - Add proxy support to subscribe, refactor proxy details into a method.
  - Add register command with proxy and satellite options and tests.
  - Create an array from the options instead of a hash.
  - Requiring all of active_support core_extensions
  - ActiveSupport v4 drops support for ruby 1.9.2

## v0.1.0
  - Building v0.1.0
  - Made sanitize a private method
  - Fixed default options to expect positive case.
  - Cleanup of commands
  - Refactored sanitizing
  - Added active_support for blank? method
  - Allow common methods to be called without namespacing.
  - Extending Yum to get the latest available version for package(s)
  - Add more options to Subscription Manager registration
  - Add a common method to sanitize user input for the command line.
  - Add common write command for use in writing config files.
  - Add parsing of Yum repo files with tests and sample data.
  - Add gem to parse files with ini type contents
  - Adding Hash store_path
  - Extend Yum.update to allow an optional list of packages as arguments.
  - Add test and support for using yum's repotrack tool.
  - Add test and support for using yum's createrepo tool.
  - Added tests and support for RPM.
  - Adding dependency for other core extensions.
  - Fix issue related to command output filling up the IO pipe.
  - Removing JRuby, Rubinius and MRI 1.8 because of Kernel.spawn support.
  - Fix misnamed .travis.yml file
  - Adding Version Badge

## v0.0.1
  - Adding Gemnasium support
  - Adding Coveralls support
  - Adding CodeClimate support
  - Adding travis-ci support
  - Adding example for Red Hat Subscription Manager hosted
  - '.registered?' should return false rather than raise if not available.
  - Adding support and tests for SubscriptionManager
  - Extending Common.run with option ':return_output'
  - Added support to mock command output sourced from a data file for tests
  - Adding tests for Yum commands
  - Adding tests for linux_admin
  - Updating Yum methods to leverage changes in Common module
  - Extending common and adding tests
  - Cleaner way to get the exitstatus of the shell process.
  - Yum commands should return true-false or raise an exception
  - Adding high level method to check system registration status
  - Adding tests for RHN functionality.
  - Adding support for RHN and method to check registeration status
  - Adding support for Yum (check and apply updates)
  - Adding a module for shared methods.
  - Adding rspec for testing.
  - Gem Framework added.