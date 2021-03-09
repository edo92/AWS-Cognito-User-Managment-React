# AWS Cognito Login with React

---

## Cognito configs

    - In `Login-Cognito/src/userPool.js` file change your `UserPoolId` and `ClientId`

- UserPoolId can be found in
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/poolid.png"/>
  </p>

- ClientId can be found in
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/app-client-settings-clientid.png"/>
  </p>

<br/>
<br/>

## AWS Cognito Setup

    - AWS Cognito User managment with signup, login, and forgot password options

- Navigate to AWS Cognito
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/goto-cognito.png"/>
  </p>

- Create User Pool
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/create-user-pool.png"/>
  </p>

- Name Your User Pool
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/name-user-pool.png"/>
  </p>

- Initial Settings that cannot be changed after creating
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/initial-settings.png"/>
  </p>

- Password Strength Settings
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/password-strength-settings.png"/>
  </p>

- Two Factor authentication settings
  <p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/two-factor-authentication-setitngs.png"/>
  </p>

- Custom Email Address Settings
<p>
   <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/custom-email-settings.png"/>
 </p>

- Email Verification Settings
<p>
   <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/email-verification-settings.png"/>
 </p>

- User Invitation Settings
<p>
   <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/user-initation-settings.png"/>
 </p>

- [Remember User Settings](https://aws.amazon.com/premiumsupport/knowledge-center/cognito-user-pool-remembered-devices/)
<p>
   <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/remember-user-settins.png"/>
 </p>

- User Access Settings
<p>
   <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/user-access-settings.png"/>
 </p>

- User pool access settings, give name, uncheck `Generate client secret` 
<p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/user-pool-access-settings.png"/>
 </p>


- We can setup custom lambda triggers
<p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/custom-triggers-settings.png"/>
 </p>

- Review and Create
<p>
    <img src="https://github.com/edo92/AWS-Cognito-User-Managment-React/blob/docs/images/review-create.png">
 </p>
