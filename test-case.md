# Test case creation

## Feature: Login
```bash
As a user
I want to be able to login to voila
So that I can access my account and purchase 
	Scenario: Success Login
    Given I am on the login page
    When I enter valid credentials
    And click on the login button
    Then I should be redirected to the account page
  Scenario: Incorrect Password
    Given I am on the login page
    When I input with valid email and incorrect password
    And click on the login button
    Then I should see an error message
  Scenario: Invalid Email
    Given I am on the login page
    When I enter an invalid email address
    And click on the login button
    Then I should see an error message
 Scenario: Empty Fields
    Given I am on the login page
    When I leave the email and password fields empty
    And click on the login button
    Then I should see an error message
```

```bash
## Feature: history order, account information on account page
As a user
I want to be able to access account page and edit them
So that I can see my history order, see my account details and edit my account details
Scenario: See latest history order on account page if i have 5 or more history order
    Given I am on the account page
    When I have more than 5 history order
    Then I should see 5 latest history order
Scenario: See latest history order on account page if i have less than 5 history order
    Given I am on the account page
    When I have less than 5 history order
    Then I should see all the latest history order
Scenario: See latest history order on account page if i have empty history order
    Given I am on the account page
    When I have empty history order
    Then I should see a message indicating that you don't have history order
Scenario: Add new address
    Given I am on the account page
    When I click see address
    And I click add new address
    And I input all mandatory field
    And I click Add address
    Then I should success adding my new address
Scenario: update address
    Given I am on the account page
    When I click see address
    And I click edit in any address that i have
    And I input all mandatory field that wanted to be changed
    And I click update address
    Then I should success adding my new address
```

```bash
## Feature: Marketplace Search
  As a user
  I want to be able to search for products on the marketplace
  So that I can find what I am looking for
	Scenario: Success Product Search
    Given I am on the main page
    When I click search button
    And I enter a valid search query
    And click on the search button
    Then I should see a list of relevant products
Scenario: No Results Found
    Given I am on the marketplace homepage
    When I enter a search query that does not match any products
    And click on the search button
    Then I should see a message indicating no results were found
Scenario: Search Filters
    Given I am on the marketplace homepage
    When I enter a valid search query
    And select a search filter
    And click on the search button
    Then I should see a list of relevant products that match the filter criteria
```