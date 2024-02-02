Project: Unittests and Integration Tests
Author: Samuel Atiemo

Project Tasks:

0. Parameterize a unit test
mandatory
Familiarize yourself with the utils.access_nested_map function and understand its purpose. Play with it in the Python console to make sure you understand.

1. Parameterize a unit test
mandatory
Implement TestAccessNestedMap.test_access_nested_map_exception. 

2. Mock HTTP calls
mandatory
Familiarize yourself with the utils.get_json function.

3. Parameterize and patch
mandatory
Read about memoization and familiarize yourself with the utils.memoize decorator.

4. Parameterize and patch as decorators
mandatory
Familiarize yourself with the client.GithubOrgClient class.

5. Mocking a property
mandatory
memoize turns methods into properties. Read up on how to mock a property (see resource).

6. More patching
mandatory
Implement TestGithubOrgClient.test_public_repos to unit-test GithubOrgClient.public_repos.

7. Parameterize
mandatory
Implement TestGithubOrgClient.test_has_license to unit-test GithubOrgClient.has_license.

8. Integration test: fixtures
mandatory
We want to test the GithubOrgClient.public_repos method in an integration test. That means that we will only mock code that sends external requests.

9. Integration tests
#advanced
Implement the test_public_repos method to test GithubOrgClient.public_repos.


