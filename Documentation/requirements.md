# Onboarding Flow for Employers & Talent Partners

---

## 1. Landing Page

**Description:** The user's journey begins on the landing page, which must have a clear call-to-action button to initiate the sign-up or sign-in process.

---

## 2. Sign In / Sign Up Modal

**Description:** Upon clicking the call-to-action, a modal will appear, presenting options for both new and existing accounts.

* **Microcopy:**
    * **Fields:**
        * "Email Address" (placeholder)
        * "Password" (placeholder)
    * **Buttons & Links:**
        * "Forgot Password?" (link)
        * "Sign In" (button)
        * "Don't have an account?" (text)
        * "Sign Up" (link)

---

## 3. Role Selection Modal

**Description:** When a user clicks "Sign Up," a new modal will appear, prompting them to select their user type. This is the first major decision point in the onboarding flow.

* **Options:**
    * **"Employer"** (Button)
    * **"Talent Partner"** (Button)

* **Logic:**
    * Clicking **"Employer"** redirects the user to the Employer Registration Form.
    * Clicking **"Talent Partner"** redirects the user to the Talent Partner Registration Form.

---

## 4. Employer Registration Form

**Description:** This form captures essential information for creating a new employer account.

* **Fields:**
    * Full Name: Text input
    * Email Address: Email input
    * Password: Password input
    * Confirm Password: Password input

* **Microcopy:**
    * **"Full Name"** (label)
    * **"Email Address"** (label)
    * **"Password"** (label)
    * **"Confirm Password"** (label)
    * **"Create your free account"** (button)
    * **"Already have an account?"** (text)
    * **"Sign In"** (link)
    * **"Switch to Talent Partner"** (link to change role)

* **Validation:**
    * **Full Name**: Required. Cannot be empty.
    * **Email Address**: Required. Must be a valid email format.
    * **Password**: Required. Must be at least 8 characters long and contain at least one uppercase letter, one lowercase letter, one number, and one special character.
    * **Confirm Password**: Required. Must exactly match the **"Password"** field.

---

## 5. Talent Partner Registration Form

**Description:** This form captures essential information for creating a new Talent Partner account.

* **Fields:**
    * Full Name: Text input
    * Email Address: Email input
    * Password: Password input
    * Confirm Password: Password input

* **Microcopy:**
    * **"Full Name"** (label)
    * **"Email Address"** (label)
    * **"Password"** (label)
    * **"Confirm Password"** (label)
    * **"Create your free account"** (button)
    * **"Already have an account?"** (text)
    * **"Sign In"** (link)
    * **"Switch to Employer"** (link to change role)

* **Validation:**
    * **Full Name**: Required. Cannot be empty.
    * **Email Address**: Required. Must be a valid email format.
    * **Password**: Required. Minimum 8 characters, with at least one uppercase letter, one lowercase letter, one number, and one special character.
    * **Confirm Password**: Required. Must exactly match the **"Password"** field.

---

## 6. Email Verification

**Description:** After submitting either registration form, a verification email is sent to the user's provided email address.

* **Logic:**
    * The user must click the verification link in the email to activate their account.
    * Upon successful verification, a dedicated success page or modal will be displayed.

* **Microcopy:**
    * "Account created successfully."

---

## 7. Employer Profile & Company Details

**Description:** This screen prompts the user to provide additional company information to enhance their profile. This step is optional and can be skipped.

* **Fields:**
    * Company Website Link: URL input
    * LinkedIn Link: URL input
    * Company Description: Text area

* **Microcopy:**
    * **"Company Website Link"** (label)
    * **"LinkedIn Link"** (label)
    * **"Company Description"** (label)
    * **"Next"** (button)
    * **"Skip"** (link)

* **Validation:**
    * **Company Website Link**: Optional. If provided, must be a valid URL format.
    * **LinkedIn Link**: Optional. If provided, must be a valid URL format.

---

## 8. Talent Partner Profile & Details

**Description:** This screen is for the talent partner to provide more detailed profile information. This step is optional and can be skipped.

* **Fields:**
    * Company Website Link: URL input
    * LinkedIn Link: URL input
    * About Yourself: Text area

* **Microcopy:**
    * **"Company Website Link"** (label)
    * **"LinkedIn Link"** (label)
    * **"About Yourself"** (label)
    * **"Next"** (button)
    * **"Skip"** (link)

* **Validation:**
    * **Company Website Link**: Optional. If provided, must be a valid URL format.
    * **LinkedIn Link**: Optional. If provided, must be a valid URL format.

---

## 9. Invite Team Members

**Description:** This screen allows users (both Employers and Talent Partners) to invite team members to their organization's account. This is an optional and skippable step.

* **Fields:**
    * Email: Email input, with the functionality to add multiple email addresses.

* **Microcopy:**
    * **"Team Member Email"** (label)
    * **"Send Invite"** (button)
    * **"Next"** (button)
    * **"Skip"** (link)

* **Validation:**
    * Each email entered must be a valid email format.

---

## 10. Dashboard & Initial Prompt

**Description:** After completing the previous steps (or skipping them), the user will be redirected to their main dashboard. An initial prompt will appear to guide them on their first action.

* **Logic:**
    * **Trigger:** A modal should appear automatically 2 seconds after the dashboard loads.
    * **Microcopy:** The modal will have friendly, encouraging content prompting the user to **"Post a Job"** (for Employers) or **"Find a Job"** (for Talent Partners).
    * **Behavior:** The modal can be closed by the user at any time.
