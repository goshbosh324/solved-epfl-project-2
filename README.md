Download Link: https://assignmentchef.com/product/solved-epfl-project-2
<br>
<h1>Option A – Machine Learning for Science</h1>

Pick a real-world challenge offered by any research group of the (extended) EPFL campus, subject to availability. You learn about an interesting application domain, and collaborate with the lab to apply machine learning methods to their specific research question, on real data provided by the lab – an exciting option to follow an interdisciplinary approach to find new insights with your team.

Deliverables at a glance.            (More details and grading criteria further down)

<ul>

 <li>Written Report. You will write a maximum 4 page PDF report on your findings, using LaTeX.</li>

 <li>In Python. External libraries are allowed, if properly cited.</li>

</ul>

The guidelines for the projects are the same as in the standard tasks explained below.

Participation of the Hosting Lab. The only major difference to the other options is that here, you do this project in collaboration with another lab on EPFL campus. The lab hosting you will help us grading the domainspecific merit of your contribution. We encourage you to reach out to any lab of your choice at EPFL, UniL, CERN, CHUV, Idiap etc., and ask them for a project idea, or propose an idea to them.

Here is a list of labs which already have proposed several exciting project ideas. Note that other labs are possible as well.

<a href="https://docs.google.com/spreadsheets/d/1Mav7vND2dYghHQxLEXqnvLZ1z9GKRcNynOAjwcQpMPo/">https://docs.google.com/spreadsheets/d/1Mav7vND2dYghHQxLEXqnvLZ1z9GKRcNynOAjwcQpMPo/ </a>Important Logistics: You can only sign up for this option if the <em>professor </em>of that lab agrees to host your group of 3 students, and will confirm this by filling the mandatory registration form for labs, by November 15th:

<a href="https://goo.gl/forms/0ElZtbKGz4U0lCag1">https://goo.gl/forms/0ElZtbKGz4U0lCag1</a>

Submission URL for the final project: <a href="http://mlcourse.epfl.ch/">http://mlcourse.epfl.ch</a> (same as for option B)

<h1>Option B – One of our Pre-defined Challenges</h1>

Deliverables at a glance.            (More details and grading criteria further down)

<ul>

 <li>Written Report. You will write a maximum 4 page PDF report on your findings, using LaTeX.</li>

 <li>In Python. External libraries are allowed, if properly cited.</li>

 <li>Competitive Part. To give you immediate feedback and a fair ranking, we use the competition platform AIcrowd.com to score your predictions. You can submit whenever and almost as many times as you like, up until the final submission deadline.</li>

</ul>

Pick Your Favorite Among Three Challenges. Pick your favorite competition among the following three online competitions. Don’t be influenced by their seemingly different difficulty level, since your contribution as compared to standard approaches will be taken into account in the grading.

<h2>Step 1 – Getting started</h2>

In order to be able to access the challenges, please first create an account at AIcrowd.com using your @epfl.ch email address. Pick your favorite competition among the following three. To read the description and download the dataset, please follow the corresponding links:

<a href="https://www.aicrowd.com/challenges/epfl-ml-text-classification-2019">https://www.aicrowd.com/challenges/epfl-ml-text-classification-2019 </a><a href="https://www.aicrowd.com/challenges/epfl-ml-road-segmentation-2019">https://www.aicrowd.com/challenges/epfl-ml-road-segmentation-2019 </a><a href="https://www.aicrowd.com/challenges/epfl-ml-recommender-system-2019">https://www.aicrowd.com/challenges/epfl-ml-recommender-system-2019</a>

For all three possible tasks, we provide some additional description and sample code on the course github:

<a href="https://github.com/epfml/ML_course/tree/master/projects/project2">https://github.com/epfml/ML_course/tree/master/projects/project2</a>

<h2>Step 2 – Implement ML Methods</h2>

You are allowed to use any external library and ML techniques, as long as you properly cite any external code used.

<h2>Step 3 – Submitting your Predictions</h2>

Once you have a working model (using the above methods or a modified one), you can send your predictions to the AIcrowd competition to see how your model is doing against the other teams. You can submit whenever and as many times as you like, until the deadline.

Your predictions must be in .csv format, see sample-submission.csv. You must use the same datapoint ids as in the test set test.csv. To generate .csv output from Python, use our provided helper functions in helpers.py (see Project 1 folder on github).

After a submission, AIcrowd will compute your score on the test set, and will show you your score and ranking in the leaderboard.

Do not use the AIcrowd score as the only estimate of your error. Instead, always estimate your test error by using a local validation set, or local cross-validation! This is important to avoid overfitting the test set online. Also, it allows you to make experiments faster, and save uploading bandwidth :). You are only allowed a maximum of 5 submissions per person to AIcrowd per day.

<h2>Step 4 – Final Submission of Your Project</h2>

Your final submission to the online system (a standard system as used for scientific conferences) must consist of the following:

<ul>

 <li>Report: Your 4 page report as .pdf</li>

 <li>Code: The complete executable and documented Python code, as one .zip file. Rules for the code part:

  <ul>

   <li><em>Reproducibility: </em>In your submission, you must provide a script run.py which produces <em>exactly </em>the same .csv predictions which you used in your best submission to the competition on AIcrowd. This includes a clear ReadMe file explaining how to reproduce your setup, including precise training, prediction and installation instructions if additional libraries are used – the same way as if you would ideally instruct a new teammate to start working with your code.</li>

   <li><em>Documentation: </em>Your ML system must be clearly described in your PDF report and also welldocumented in the code itself. A clear ReadMe file must be provided. The documentation must also include all data preparation, feature generation as well as cross-validation steps that you have used.</li>

   <li><em>External ML libraries </em>are allowed, as long as accurately cited and documented.</li>

   <li><em>External datasets </em>are allowed, as long as accurately cited and documented.</li>

  </ul></li>

</ul>

Submission URL: <a href="http://mlcourse.epfl.ch/">http://mlcourse.epfl.ch</a>

Don’t forget to provide all author names with their EPFL email, as well as the (correct one and only one!) ranking username appearing AIcrowd, and select the right one of the 3 tasks. You can update all parts of your submission anytime until the deadline.

<h1>Option C – ICLR Reproducibility Challenge</h1>

Your team participates in the ICLR/NeurIPS Reproducibility Challenge. Here the goal is to select a new submitted ICLR or NeurIPS paper, and try to reproduce (parts of) its experiments: (Subject to availability in

2020) <a href="https://reproducibility-challenge.github.io/neurips2019/">https://reproducibility-challenge.github.io/neurips2019/</a>

<a href="https://reproducibility-challenge.github.io/iclr_2019/">https://reproducibility-challenge.github.io/iclr_2019/</a>