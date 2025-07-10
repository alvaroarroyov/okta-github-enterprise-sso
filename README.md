# 🔐 Okta + GitHub Enterprise SSO Integration

This project demonstrates a simulated SSO (Single Sign-On) integration between **Okta** and **GitHub Enterprise** using **SAML 2.0**. It includes screenshots, SAML assertion samples, and a complete configuration walkthrough.

---

## 🧠 Objectives

- Configure Okta as the Identity Provider (IdP)
- Configure GitHub Enterprise as the Service Provider (SP)
- Enable SSO via SAML
- Analyze SAML assertions
- Document the authentication flow

---

## 🧰 Technologies Used

- ✅ Okta Admin Console (Free Developer Account)
- ✅ GitHub Enterprise (simulated setup)
- ✅ SAML 2.0
- ✅ XML 
- ✅ Draw.io (for diagrams)

---

## 📸 Screenshots

| Step | Description |
|------|-------------|
| ![1](images/okta_app_config.png) | Okta SAML App Configuration |
| ![2](images/github_sso_config.png) | GitHub Enterprise SSO Configuration |
| ![3](images/okta_app_saml_certficiate_and_mfa.png) | SAML Certificates and MFA Authentication |
| ![4](images/saml_assertion.png) | Sample SAML Assertion from Okta |

---

## 📋 Step-by-Step Configuration

Full instructions available in [`steps.md`](./steps.md)

1. Create a new SAML 2.0 app in Okta.
2. Enter the GitHub ACS (Assertion Consumer Service) URL.
3. Download the metadata XML from Okta.
4. In GitHub Enterprise, go to Settings > Authentication and upload the metadata.
5. Assign test users to the Okta app.
6. Test SSO login and validate assertions.

---

## 🧪 SAML Assertion Sample

Check [`saml_assertion_example.xml`](./saml_assertion_example.xml) for a decoded assertion.

---

## 📈 Flow Diagram

![diagram](flow_diagram.png)

---

## 📩 Contact

Built by Álvaro Arroyo — [LinkedIn](https://www.linkedin.com/in/alvaro-arroyo-vasquez-910227342/)
