#Intro 
The danish FSA and the national bank recently introduced FINOA, a new system for financial institutions to report their activities to the authorities.

#The problem
The idea is good, but the current documentation of the actual reporting process lacks proper clarity and is 10x more complex than it could be. 

#The solution
Let me introduce the first open source FIONA documentation repo in GitHub 🙌 Here you can find: 
1. An example of what a successful FINOA report in .XML format looks like
2. A dictionary that explains what all the tags and values means in the .XML file from point 2. 
3. A backend export checklist that can be used to export all numbers from your data warehouse that cannot be easily found manually.

Tutorial to achieve a successful FIONA report:
1. Read the official document called "Teknisk anvisning" to understand the basics.
2. Copy the XML file to your local directory.
3. Export all numbers from your data warehouse using the backend export checklist.
4. Change all attributes on the local XML file to the correct values for your company by using the dictionary and the numbers from the backend export checklist.
5. Do a final sanity check of the XML file before uploading it to the FIONA system.
6. Upload the XML file to the FIONA system and adjust if needed.
7. Celebrate 🎉

#Technologies
This project is built with: frustration with terrible technical and overall communication clarity in the existing FINOA documentation. 

#Contributions
Contributions are welcome! Please feel free to submit a PR or open an issue. 

#License
Open source, let's learn together!