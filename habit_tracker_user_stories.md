
# User Stories for Habit Tracking App

## Login/Registration Page

### **1. Account Registration**
**As a** user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features.

#### **Acceptance Criteria:**
1. The user should be able to enter their name, username, age, and country during registration.
2. A confirmation message should be displayed upon successful registration.
3. The user should not be able to register with an already taken username.

**Priority:** High  
**Story Points:** 3  
**Notes:** The credentials will not be stored in the browser cache after logout.

---

### **2. Account Login**
**As a** user, I want to log in using my username and password so that I can access my account and track my habits.

#### **Acceptance Criteria:**
1. The user should be able to enter their username and password to log in.
2. A success message should be displayed if the login is successful.
3. If incorrect credentials are entered, an error message should appear.

**Priority:** High  
**Story Points:** 3  
**Notes:** Due to security constraints, users must log in with a default username and password.

---

## Homepage

### **3. View Welcome Message**
**As a** user, I want to see a personalized welcome message with my name on the homepage so that I feel recognized and can confirm I am logged into the correct account.

#### **Acceptance Criteria:**
1. The homepage should display the user’s name in a welcome message.
2. The welcome message should update when the user edits their profile name.
3. The message should disappear when the user logs out.

**Priority:** Medium  
**Story Points:** 2  
**Notes:** Should support multiple users with different names.

---

### **4. Display Weekly Progress**
**As a** user, I want to see my daily progress for each habit on the homepage so that I can easily monitor my progress.

#### **Acceptance Criteria:**
1. The homepage should display a progress tracker for each habit.
2. The tracker should update dynamically as habits are completed.
3. The data should be stored persistently.

**Priority:** High  
**Story Points:** 3  
**Notes:** Consider adding graphs or charts for better visualization.

---

## Menu

### **5. Access Menu Options**
**As a** user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out so that I can easily navigate to different parts of the app.

#### **Acceptance Criteria:**
1. The menu should have options for Profile, Habits, Reports, and Sign Out.
2. The menu should be accessible from any screen.
3. The menu should close when a selection is made.

**Priority:** High  
**Story Points:** 2  
**Notes:** Consider a bottom navigation bar for better usability.

---

## Profile Page

### **6. View Personal Information**
**As a** user, I want to view my saved name, username, age, and country on my profile page so that I can see the details I provided during registration.

#### **Acceptance Criteria:**
1. The profile page should display user details entered during registration.
2. The data should be read-only until the edit option is selected.
3. The profile should be accessible from the menu.

**Priority:** Medium  
**Story Points:** 2  
**Notes:** Ensure proper formatting for readability.

---

### **7. Edit Personal Information**
**As a** user, I want to update my name, username, age, and country on my profile page so that I can keep my information up to date.

#### **Acceptance Criteria:**
1. The user should be able to edit and save changes to their profile details.
2. A confirmation message should appear after saving updates.
3. The new name should reflect in the header and welcome message.

**Priority:** High  
**Story Points:** 3  
**Notes:** Data validation should be applied to prevent incorrect inputs.

---

## Habits Page

### **8. Add a New Habit**
**As a** user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed.

#### **Acceptance Criteria:**
1. The user should be able to add a habit with a name and frequency.
2. The habit should appear in the list upon creation.
3. The user should be able to assign a color to the habit.

**Priority:** High  
**Story Points:** 3  
**Notes:** Consider adding pre-set habit templates for convenience.

---

## Reports Page

### **9. View Weekly Reports**
**As a** user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits.

#### **Acceptance Criteria:**
1. The app should generate a weekly progress report.
2. Completed and incomplete habits should be displayed.
3. Data should be visually represented in graphs.

**Priority:** High  
**Story Points:** 3  
**Notes:** Ensure accessibility for color-blind users.

---

## Notifications Page

### **10. Enable/Disable Notifications**
**As a** user, I want to be able to enable or disable notifications for the app so that I can choose whether or not to receive reminders for my habits.

#### **Acceptance Criteria:**
1. The user should have a toggle to enable or disable notifications.
2. Notifications should be scheduled according to user preferences.
3. The setting should persist even after the app restarts.

**Priority:** Medium  
**Story Points:** 2  
**Notes:** Consider push notifications for better user engagement.
