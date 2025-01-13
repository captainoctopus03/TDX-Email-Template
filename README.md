# TDX-Email-Template

# README for Notification Email Template

## Overview
This email template is designed for IT helpdesk support services to notify requestors about updates to their support tickets. It uses a responsive design to ensure compatibility across various devices and email clients. The template incorporates best practices for accessibility, readability, and branding consistency.

## Features
- **Responsive Design**: Ensures the email is viewable on both desktop and mobile devices.
- **Customizable Branding**: Uses Ensign College's colors and fonts to maintain a professional and branded appearance.
- **Dynamic Content**: Includes placeholders for dynamically injected content (e.g., ticket details, comments, and user names).
- **Accessible Formatting**: Provides a clean and readable layout with high contrast and semantic HTML.

## File Structure
- **HTML Structure**: Organized into clear sections for the notification banner, header, main content, and footer.
- **CSS**: Inline styles are used to ensure consistent rendering across email clients. Media queries are included for responsive behavior.
- **Dynamic Placeholders**: Variables like `{{RequestorFirstName}}`, `{{ID}}`, and `{{Title}}` allow for dynamic content injection by the server or email platform.

## Placeholder Variables
- `{{RequestorFirstName}}`: The first name of the requestor.
- `{{NextTicketsUrl}}`: A link to view the updated ticket.
- `{{ID}}`: The unique identifier for the ticket.
- `{{Title}}`: The title of the ticket.
- `{{UpdateText}}`: The text of the latest update to the ticket.
- `{{UpdateCreatedUserFullName}}`: The name of the user who added the update.
- `{{ModifiedDate}}`: The date of the update.
- `{{KnowledgeBaseArticleUrl}}` (optional): A link to a related knowledge base article.
- `{{KnowledgeBaseArticleSubject}}`: The title of the related knowledge base article.
- `{{RequestorFullName}}`: The full name of the requestor.
- `{{ResponsibleName}}`: The name of the person responsible for the ticket.
- `{{ResponsibleGroupName}}`: The group responsible for the ticket.

## Usage Instructions
1. **Dynamic Content Injection**:
   - Use your email automation platform or backend service to replace placeholders with actual data.
2. **Customization**:
   - Update the logo URL or replace it with your organization’s logo.
   - Modify styles in the `<style>` block to match your branding guidelines.
3. **Testing**:
   - Test the email template across different email clients (e.g., Gmail, Outlook, Apple Mail) and devices (desktop and mobile).
4. **Deployment**:
   - Integrate the template with your helpdesk or email notification system.

## Styling and Layout Details
- **Fonts**:
  - `Montserrat` (sans-serif) for headers and main content.
  - `Libre Baskerville` (serif) for ticket details and notifications.
- **Colors**:
  - Background: White (`#FFFFFF`)
  - Primary: Green (`#006248`)
  - Secondary: Yellow (`#F6AA1B`)
  - Text: Black (`#000000`) and White (`#FFFFFF`)
- **Responsive Adjustments**:
  - Tables and two-column layouts adjust for smaller screen sizes using media queries (`@media screen and (max-width: 600px)`).

## Accessibility Notes
- Font sizes are chosen to ensure readability.
- Sufficient contrast between text and background colors for accessibility.
- Links are styled for visibility and include `text-decoration: none;` for a cleaner appearance.

## Additional Notes
- This template uses inline CSS for maximum compatibility with email clients.
- Add fallback mechanisms for email clients that may not support media queries.

## Example Data for Testing
Replace placeholders with example data for local testing:
- `{{RequestorFirstName}}`: "John"
- `{{NextTicketsUrl}}`: "https://www.support.com"
- `{{ID}}`: "12345"
- `{{Title}}`: "System Login Issue"
- `{{UpdateText}}`: "Your ticket has been updated with additional troubleshooting steps."
- `{{UpdateCreatedUserFullName}}`: "Jane Doe"
- `{{ModifiedDate}}`: "January 12, 2025"
- `{{KnowledgeBaseArticleUrl}}`: "https://www.support.com/article/56789"
- `{{KnowledgeBaseArticleSubject}}`: "How to Resolve Login Issues"
- `{{RequestorFullName}}`: "John Smith"
- `{{ResponsibleName}}`: "Jane Doe"
- `{{ResponsibleGroupName}}`: "IT Support Team"

## License
This template is proprietary to Ensign College and is intended for internal use only. Unauthorized redistribution or modification is prohibited.

