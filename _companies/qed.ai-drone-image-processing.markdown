---
layout: project
ordering: 3
company: qed.ai
company_img:
company_desc:
project: Drone Image Processing for Agroecological Monitoring
project_img:
technological_stack: |
    - Web: Django back-end, React front-end
    - Web Server: nginx, uWSGI, Ubuntu 16.04 LTS
    - Database: PostgreSQL
    - Mobile: React Native
methodology: |
    Our workflow is most similar to Agile, although we do not follow it very strictly. We integrate ideas from Kanban into our task management system, and have regular discussions online and via video conference whenever necessary. We employ continuous integration methods that are detailed in the answer to the following question.
shipment_method: |
    We use Gerrit and Jenkins for code review and automated testing of back-end and front-end code, coupled with QA testers who further test all features and provide ticketed feedback.  Our projects are auto-deployed to multiple cloud servers, each representing different code checkpoints with varying levels of stability. We will also engage in regular online communications.
training: |
    Given that candidates are in the final years of computer science education, we expect them to already have a few years of experience with building and deploying working software. We will provide them with a real-world problem-solving context often missing from purely academic courses.
    QED is aware that framework-specific knowledge is not as important as strong analytical skills and experience with design patterns. However, if the duration of the work contract is very short (e.g. only a few months), then it would be most efficient if candidates already know the frameworks listed above, so that they can concentrate on design and coding rather than learning new frameworks, and have sufficient time to build something substantial and useful.
tools_provided: |
    This is a strictly software-oriented project, so candidates will already have the computers they need. QED will provide all DevOps support, such as cloud infrastructure, code repositories, and buildsystems, as well as researchers and graphic designers.
mentor: |
    QED will assign experienced mentors to assist the team with high-level architectural issues and code review.
worktime: 15 hours per week per team member.
location: |
    Work is remote. However, QED may organize workshops in Warsaw, or provide developers with fully-sponsored travel to visit users on-site in other places as necessary, if this is required to better provide real-world contexts. Any such visits would be discussed with team members first before planning them.
money: |
    QED offers competitive payment on an hourly basis that is commensurate with experience and skills. 
later_employment: |
    We may offer subsequent employment if work quality is high and there is a clear team fit.
team_size: |
    We would prefer teams of 2 to 4 software engineers. QED will also provide auxiliary staff to assist them.
requirements: |
    - Python: +2 years
    - Javascript: +2 years
    - Django: +1 years
    - Strong knowledge of data structures, algorithms, and common software design patterns.
    - Fluent communication skills in both spoken and written English.
    - Genuine enthusiasm for software engineering and writing code that is clean, readable, and efficient.
    - Willingness to work with distributed teams and code reviews.
    - Deep experience working with a substantial software project, such as from prior professional work experiences, or from contributions to open source software. Provide samples of code.
    
    Preferred but not required:
    - Some experience with algorithmic or mathematical competitions.
    - Computer vision experience is a plus.
project_roles: |
    QED will work with students to design the projects together. Designs are expected to change based on user feedback, so candidates should apply a high standard of software craftsmanship to enable rapid iterations.
copyrights: |
    QED will retain the rights to the project as a paying employer. In most cases we will bring a substantial pre-existing codebase to the table, and are not starting from scratch. We are also advocates of open source, and may choose to open source components of the project, or possibly the project in its entirety, as business conditions permit.
---
__Remark__ QED does not have an office in Kraków.

Due to a scarcity of high-resolution data, agricultural and ecological researchers in Africa are particularly limited in their ability to monitor and evaluate the effects of climate change, man-made terraforming, and agronomic interventions. Development agencies often employ ground teams to execute measurements on-foot, but these operations are highly time-consuming. Remote sensing products provide alternatives for covering larger areas, but their spatial resolution is insufficient to resolve crop-specific patterns and erosion details, and historical data is often locked behind prohibitive paywalls.

UAVs have the potential to unlock critical barriers for conducting precise spatial-temporal analyses. While geosynchronous satellites fly 36,000 km above the earth, drones can operate only 100-150 m above the ground, circumventing cloud cover issues completely and achieving spatial resolutions on the order of 5 cm. Frequency of imaging is also no longer limited by satellite schedules, but rather only one’s ability to execute ground logistics. By taking overlapping photos, the parallax effect can be used to construct up-to-date digital elevation models exposing the relative heights of trees, buildings, and shrubs, as illustrated [here](https://sketchfab.com/models/24f232b03d2d4f60ae427be49fd1e13e). Lastly, drones can also be equipped with multispectral sensors to measure non-visible vegetation indices.

QED has been developing a variety of solutions for making drones practical for scientific studies, including

1. reducing the cost of purchase
2. easing the coordination of ground operations
3. providing scalable platforms for storing and processing the large datasets that result from UAV flights

For example, through using off-the-shelf or custom designed quadcopters that are 10-30x cheaper than fixed-wing drones, we have demonstrated that they are capable of generating the same orthomosaics produced by commercial software packages, when coupled with our own flight software, named [AutoDrone](https://play.google.com/store/apps/details?id=ai.qed.auto.drone&hl=en). Processing and storage is handled by our [Hive](http://hive.qed.ai/) platform, which takes the guesswork out of organizing metadata organization, handles post-processing asynchronously, and produces visualizations in the browser.  

We are looking for enthusiastic software engineers that have high standards for software craftsmanship, and are also well-trained in computer science fundamentals, to join us in developing these tools further.