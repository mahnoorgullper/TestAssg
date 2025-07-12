**Authentication**

To authenticate API requests, get the token by visiting below link
[https://gorest.co.in/my-account/access-tokens](https://gorest.co.in/my-account/access-tokens)

**Collection Details**

* A Postman collection has been created with the name **“GoRest-APIs”**.
* You can **download** and **import** this collection into Postman for testing.

 **Verifications Performed**

The collection covers four test scenarios:

1. **Happy Flow Validation**

   * Checks that the response status code is `201`. (Created user)
   * Checks that the `id` field is numeric or not.
   * Ensures the `status` value is either `"active"` or `"inactive"`.

2. **Duplicate Email Check**

   * An additional test case is included to verify the behavior when a **previously used email address** is submitted.
   * This test confirms that the API returns an appropriate error response for duplicate entries.
