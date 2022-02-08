1. Visit: https://snyk.io

![01-snyk-home-page](https://user-images.githubusercontent.com/194400/49246105-0c6c2900-f40c-11e8-9ff1-824c1f327626.png)

2. Click the "Signup with GitHub" button/link:

![02-snyk-signup](https://user-images.githubusercontent.com/194400/49246107-0c6c2900-f40c-11e8-8004-ae31a2369090.png)

3. Click the button to "Athorise Snyk":

![03-snyk-authorise](https://user-images.githubusercontent.com/194400/49246108-0c6c2900-f40c-11e8-82e9-deea841fe6bf.png)

4. Click to "Connect with GitHub":

![04-snyk-integrations-select-github](https://user-images.githubusercontent.com/194400/49246110-0d04bf80-f40c-11e8-9729-9aa52fd7965e.png)

5. _Again_ click "Connect with GitHub":

![05-connect-to-github](https://user-images.githubusercontent.com/194400/49246112-0d04bf80-f40c-11e8-88b2-ef608def7cb0.png)

6. By default Snyk requests access to both **`public`**  and **`private`**  repos,
Select whatever is relevant to you and continue:

![06-snyk-wants-private-repos-by-default](https://user-images.githubusercontent.com/194400/49246113-0d04bf80-f40c-11e8-9766-2c3cf6f4938a.png)

7. I selected _only_ **`public`** repositories as I _always_ follow the ["principle of least privilege"](https://github.com/dwyl/learn-security#principle-of-least-privilege):

![07-snyk-select-public-repos-only](https://user-images.githubusercontent.com/194400/49246115-0d04bf80-f40c-11e8-9a8a-ca322d79cea1.png)

8. Confirm the access that Snyk is requesting:

![08-snyk-authorise](https://user-images.githubusercontent.com/194400/49246117-0d9d5600-f40c-11e8-825f-1bdab8ac318c.png)

9. Connect to Snyk to a GitHub Repository:

![09-snyk-connect-to-github-repo](https://user-images.githubusercontent.com/194400/49246118-0d9d5600-f40c-11e8-9898-0ccbc2041279.png)

10. Select the desired repository: (_in this case [`hapi-auth-jwt2`](https://github.com/dwyl/hapi-auth-jwt2) ..._)

![10-snyk-select-desired-repo](https://user-images.githubusercontent.com/194400/49246119-0d9d5600-f40c-11e8-9820-1cea4e45f90a.png)

11. Add selected repo:

![11-snyk-add-1-selected-repository](https://user-images.githubusercontent.com/194400/49246121-0d9d5600-f40c-11e8-81bb-d7eb283a2f0f.png)

12. Wait for the repo to be imported by Snyk:

![12-snyk-importing](https://user-images.githubusercontent.com/194400/49246122-0d9d5600-f40c-11e8-91a2-e0bb28439f83.png)

13. Once the repo has finished importing, refresh the page to see your dashboard:

![13-snyk-finished-securing](https://user-images.githubusercontent.com/194400/49246123-0e35ec80-f40c-11e8-9d5b-e73abe619ae7.png)

14. From the Snyk dashboard. Click on the project you want to view:

![14-snyk-dashboard-projects](https://user-images.githubusercontent.com/194400/49246124-0e35ec80-f40c-11e8-87fb-3c15615ebef8.png)

15. Copy the Snyk "Badge" for inclusion in your project:

![15-snyk-project-page](https://user-images.githubusercontent.com/194400/49246125-0e35ec80-f40c-11e8-8347-6030901931da.png)


Badge Format:
```
[![Known Vulnerabilities](https://snyk.io/test/github/{username}/{repo}/badge.svg)](https://snyk.io/test/github/{username}/{repo})

```

Official Badge: [![Known Vulnerabilities](https://snyk.io/test/github/dwyl/hapi-auth-jwt2/badge.svg?targetFile=package.json)](https://snyk.io/test/github/dwyl/hapi-auth-jwt2?targetFile=package.json)
```
[![Known Vulnerabilities](https://snyk.io/test/github/dwyl/hapi-auth-jwt2/badge.svg?targetFile=package.json)](https://snyk.io/test/github/dwyl/hapi-auth-jwt2?targetFile=package.json)
````

Flat Square: [![Known Vulnerabilities](https://snyk.io/test/github/dwyl/hapi-auth-jwt2/badge.svg?targetFile=package.json&style=flat-square)](https://snyk.io/test/github/dwyl/hapi-auth-jwt2?targetFile=package.json)
```
[![Known Vulnerabilities](https://snyk.io/test/github/dwyl/hapi-auth-jwt2/badge.svg?targetFile=package.json&style=flat-square)](https://snyk.io/test/github/dwyl/hapi-auth-jwt2?targetFile=package.json)
```

> Note: _just_ having a 3rd party service telling you there aren't any ***know vulnerabilities***
does ***not guarantee*** that your app is "_secure_"! You still need to write
good code that escapes all input and follows "best practice"!
But the `snyk` badge & service is a _useful_ early warning system.