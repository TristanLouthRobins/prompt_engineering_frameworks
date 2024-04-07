COMPOSITE ENGINEERED PROMPT

# CONTEXT:

I would like you to create a mock dataset consisting of text fields as if they were derived from LinkedIn. Following these initial instructions, I will provide an additional prompt for the type of LinkedIn user I would like you to create a mock data set for.

# INSTRUCTIONS:

For the mock dataset, you will need to break the text fields into the following sections:

1. Name (Name and current position of the user profile) 
This will consist of a made up name (first name and surname) followed by their current position. In the following prompt, I will provide this an input so all you will need to do is replicate this in your output.

2. About
This section will consist of two to three paragraphs written in the first person, where the user is detailing their professional biography, consisting of work roles and notable achievements.

3. Experience
This section will consist of a summary of their educational qualifications and work history (i.e. positions held.) It is important to consider the candidate's current role when listing their education qualifications. In the following prompt (in addition to providing their name and current role) I will provide their date of birth, so that you will be able to better determine their number of educational qualifications and work positions held. Consider that if they hold a current 'senior' or advanced work role then this would mean they hold a post-graduate qualification.

4. Skills and Endorsements
This section will list the user's core 'Skills' with a subsection consisting of endorsements from their LinkedIn network. For determining their skills, you will derive this from their 'About' and 'Experience' text. Limit their core skills to no more than 10 skills. In the 'Endorsement' subsection, include a testimonial from a person in their LinkedIn network. As an indicator for how many testimonials to include, for each core skill limit this to no more than 2 use the number of connections in their network to determine how many endorsements they receive - so for example, if they have 500 connections then this might equate to lots of endorsements, compared to a user profile with less than 100 connections. I will include their number of connections in the following prompt. Also, it is important to consider the user's 'Experience' when determining the number of endorsements, so if they have a comprehensive work history with a clear career progression, then this would result in more endorsements. If the user has less than 100 LinkedIn connections, then do not list any endorsements and instead print "NONE."

# INPUT DATA: 
As input data, I will provide the following: 

1. User's name and their current position: for the 'Name' section of the dataset 
2. The user's year of birth: for you to determine their 'Experience'
3. The user's number of LinkedIn connections: for you to determine how many 'Endorsements' they receive relevant to their skills. Please include this number in the 'Name' section

# OUTPUT:
Important: only output mock data when I have provided a follow-up prompt.

As I have previously indicated, please output the dataset in the following sections:
"NAME"
"ABOUT" - no more than three paragraphs, written in the first person.
"EXPERIENCE" - bullet point their educational and work history
"SKILLS AND ENDORSEMENTS" - bullet point their skills, with endorsements listed below this.
