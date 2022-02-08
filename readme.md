# VICTORY HEALTH TECH

### Victory Health Tech's ultrafast Progressive Web App

------------------------------------------------------------------------

## LICENSE

This is the company website for <http://victoryhealthtech.com>.

All code is available via MIT license.

However, please note, the Victory Health Tech logo, all original artwork, and original written copy pertaining specifically to Victory Health Tech are proprietary and may not be duplicated.  However, you're free to clone this repo and refactor the code therein and incorporate your own styling to generate another website with similar functionality.  Please do not replicate any proprietary styling or brand related features--i.e., visual or written elements--of the Victory Health Tech website on your own URL without the express written permission to do so.  Attribution / credit is appreciated but not required.

------------------------------------------------------------------------

## ACKNOWLEDGEMENTS

Special thanks to Danny Moerkerke for sharing his insights on optimizing PWA design, and intercepting and streaming requests / responses via a service worker script.


------------------------------------------------------------------------

## ARCHITECTURE

The site is designed to be visually unique and non-boilerplate. It is extremely performant on all devices, everything validates well, and the infra choices make it easily scalable.

In summary, the AWS services used are:

* Route53
* ACM (with two certs)
* Global Accelerator
* ALB
* Target Group
* VPC (with one subnet)
* EC2
* S3 (static content and logs)
* CloudFront (for static CDN)

------------------------------------------------------------------------

## DIRECTORY STRUCTURE

All styling, images, and scripts can be found in the src directory.

Every page should have a dedicated top-level directory, and--within that directory--an index.html file.

Moreover, every component in the DOM will have its own corresponding template and javacript file in the templates directory.

Routing is managed in the service-worker.js file.

------------------------------------------------------------------------

## TO INSTALL AND LAUNCH APP LOCALLY

* clone this repo onto the server.

* npm install

* npm start

* dial into localhost:9090

------------------------------------------------------------------------

## CHANGELOG (FEB 2022)

* initial commit

------------------------------------------------------------------------

## TO DO

* implement better styling

------------------------------------------------------------------------

## CONTACT

Feel free to e-mail BlogBlimp and make suggestions or ask questions.  Your input is highly valued. Email your comments and inquiries to:

sean@blogblimp.com
