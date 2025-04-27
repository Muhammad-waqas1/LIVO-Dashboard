Vendor & Admin Dashboard
========================

Overview
--------

This project includes a secure and responsive **Login System**, **Vendor Dashboard**, and **Admin Dashboard**, built for easy management and smooth user experience.

### Features

*   **Login Page**
    
    *   Company login + User login fields.
        
    *   **Forgot User** under email input:
        
        *   Pops up a card with guidance (default user, email login tips, support link).
            
    *   **Forgot Password** link:
        
        *   Redirects to a **separate page** with "Remind Password" form (Company login + User login input).
            

Technologies Used
---

*   HTML5, CSS3
    
*   JavaScript
    
*   Bootstrap 4/5
    
*   jQuery (for popup handling)
    
*   Custom CSS and JS for animations
    

Special Notes
----

*   Forgot user popup provides default username suggestions for accounts before/after **12-12-2022**.
    
*   Forgot password is handled on a separate styled page, ensuring security.
    
*   Support integration ready (chat button placeholders included).
    

Deployment Notes
----------------

*   Link backend endpoints properly for login and password reminder.
    
*   Ensure email and username checks are updated server-side.
    
*   Connect Vendor/Admin roles after successful login redirection.
    

Support
-------

For any login issues, users are guided to **Contact Support** directly from the Forgot User popup.