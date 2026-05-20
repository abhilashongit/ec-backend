# ec-backend
This is the 'use' readme for this project

**Typography Usage Guide**
A clean, scalable typography system for consistent brand communication across the website.

Philosophy
This typography system is intentionally minimal.
The goal is to create a clear distinction between:


Brand Expression → handled by the AirIndia font family


Operational / Functional Communication → handled by the Nunito font family


This separation prevents visual clutter, improves readability, and maintains a strong consulting-grade visual identity.

Font Roles
AirIndia (Brand Display Font)
Used for:


Hero headlines


Brand statements


Strategic messaging


High-impact section headers


Premium visual moments


Purpose:


Create authority


Establish distinction


Signal transformation and innovation


Files


AirIndiaVariable.ttf → Preferred production font


AirIndia-Regular.ttf → Fallback/static version


Recommended Usage
Use AirIndia only where attention and emphasis are required.
Examples:


Homepage hero


Core messaging


Campaign banners


Transformation narratives


Key landing page statements


Do NOT Use AirIndia For


Paragraphs


Dense UI


Forms


Tables


Dashboards


Long-form content


Captions


Navigation-heavy sections


Overusing AirIndia weakens brand impact and reduces readability.

Nunito (Operational / Content Font)
Used for:


Body copy


Product/service descriptions


UI text


Buttons


Navigation


Forms


Supporting content


Data-heavy sections


Purpose:


Maintain clarity


Improve readability


Support scalable UI systems


Keep consulting communication clean and structured


Files


Nunito-Regular.ttf


Nunito-Medium.ttf


Nunito-MediumItalic.ttf


Nunito-SemiBold.ttf


Weight Guidance
WeightUsageRegularBody copy, descriptionsMediumSupporting emphasisMedium ItalicQuotes, secondary emphasisSemiBoldButtons, labels, UI emphasis

Typography Hierarchy
ElementFontHero HeadlinesAirIndiaBrand StatementsAirIndiaBrand-focused Section HeadersAirIndiaWork/Execution-focused HeadersNunito SemiBoldBody CopyNunito RegularUI ComponentsNunitoButtonsNunito SemiBoldFormsNunitoTables/DataNunito

Core Rules
1. Use AirIndia Sparingly
AirIndia is a display font — not a utility font.
The more selectively it is used, the stronger the brand impact becomes.

2. Prioritize Readability
Operational clarity always takes precedence over visual experimentation.
If content is:


dense,


instructional,


data-heavy,


interactive,


use Nunito.

3. Avoid Typography Clutter
Do not:


mix excessive font weights,


combine multiple heading styles unnecessarily,


stack decorative typography,


use AirIndia inside functional UI sections.


Consistency beats novelty.

Recommended CSS Structure
:root {  --font-brand: "AirIndiaVariable", sans-serif;  --font-content: "Nunito", sans-serif;}
Example usage:
.hero-title {  font-family: var(--font-brand);}.body-text,.form-input,.button {  font-family: var(--font-content);}

Production Recommendation
Prefer:
AirIndiaVariable.ttf
Reasons:


Better scalability


Cleaner responsive typography


Improved performance vs multiple static variants


Easier future expansion


Use AirIndia-Regular.ttf only as a fallback/static compatibility option.

Final Principle
Typography should reinforce positioning — not compete for attention.
AirIndia creates identity.
Nunito delivers clarity.
The system works only when both fonts stay within their intended roles.
