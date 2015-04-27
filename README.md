# Changes to be made (reference Sauce Account)

Change line 35:

Previous:
`public SauceOnDemandAuthentication authentication = new SauceOnDemandAuthentication("...", "...");`

Should be: `public SauceOnDemandAuthentication authentication = new SauceOnDemandAuthentication(YOUR_USERNAME, YOUR_ACCESS_KEY);`

# Running the tests
to run: `mvn test`
