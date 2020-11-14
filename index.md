<center><img width="517" alt="pybrain_logo" src="pybrain_logo.png"></center>

The python for brain imaging (pybrain) workshop series is for practicing neuroimagers
who want to learn more about how to work with data in Python. We assume no previous
Python background, and provide a comprehensive hands-on introduction to state of the art
libraries for experiment building, statistical modelling, machine learning, and
multimodal neuroimaging analysis.

The workshops are hosted by the [MRC Cognition and Brain Sciences
Unit](https://www.mrc-cbu.cam.ac.uk/) at the University of Cambridge, and will run
online with Zoom.
 
# Schedule

Workshops will run Mondays and Tuesdays, and generally take place 9:30am-12:00pm and
13:00pm-15:30pm GMT. There is separate registration for each workshop, but please do
sign up for Edwin's introductory session if you've never worked with Python before.

## 2-3 November 2020: Introductory python, basic data analysis, experiment coding

*[Edwin Dalmaijer](http://www.pygaze.org/esdalmaijer/), MRC CBU, University of
Cambridge, UK*

[registration](https://www.eventbrite.co.uk/e/pybrain-introductory-python-basic-data-analysis-experiment-coding-tickets-122958370797)

[instructions](http://www.pygaze.org/2020/10/pybrain-workshop)

[materials and notebooks](https://github.com/esdalmaijer/PyBrain_Python_Intro)

### Timings

This workshop runs 9:30am - 15:30pm both days. We have breaks scheduled 10:30am-11:00am,
12:00-13:00pm, and 14:00-14:30pm, during which time you may be expected to work
independently on exercises. Please consult the instructions above before the workshop.

Registered attendees will receive an email with the Zoom meeting details. **Please check
your bulk/spam email folders if you are registered and haven't heard from us by now, as
Eventbrite emails often get marked as spam**

#### 2 November
* Introduction to Jupyter Notebooks
* Variables and variable types
* Writing your own functions
* What are classes, and how do I write my own?
* Basic data handling, from loading to plotting

#### 3 November
* Implementing statistical tests
* Model fitting through minimisation
* A quick look at experiments\*
* Using Python at home and/or in the lab

\* While we will be going over how to code experiments, we won't be able to run them in
our online environment. You'll thus have to apply what you learned at a later time.

## 9-10 November 2020: MRI analysis in Python using [Nipype](https://nipype.readthedocs.io/en/latest/), [Nilearn](https://nilearn.github.io/) and more

*[Michael Notter](https://miykael.github.io/), University of Lausanne, Switzerland and
[Peer Herholz](https://peerherholz.github.io/), MNI, McGill University, Canada*

[registration](https://www.eventbrite.co.uk/e/pybrain-mri-analysis-in-python-using-nipype-nilearn-and-more-tickets-123243136539)

#### Instructions

For this workshop you will need to install [Docker Desktop](https://www.docker.com/products/docker-desktop) on your system. Please follow [these instructions](https://github.com/miykael/workshop_pybrain#1-docker-recommended-fully-interactive) to setup your system. Please be aware that the download of the workshop content might take some time, as it includes the download of a docker image of ~10GB. If you run into problems, please let us know [by creating a new issue here](https://github.com/miykael/workshop_pybrain/issues).

You are ready for the workshop and good to go, if you can open the Jupyter Notebook `program.ipynb` and see [something like this](https://nbviewer.jupyter.org/github/miykael/workshop_pybrain/blob/master/workshop/program.ipynb).

### Timings

This workshop runs from 09:30 to 15:30 both days. Lunch breaks are scheduled from 12:00 to 13:00. Individual short breaks can be taken during the multiple independent exercise sessions throughout the workshop. Please consult the instructions above before the workshop. Be aware, that the setting up of your system might take some time, as it includes the download of a docker image of about 10GB.

Registered attendees will receive an email with the Zoom meeting details by November 4. **Please check your bulk/spam email folders if you are registered and don't hear from us by this date, as Eventbrite emails often get marked as spam**

#### 9th November
* `09:30-10:00` - Workshop overview
* `10:00-10:45` - Quick recap on Jupyter, Python and more\*
* `10:45-12:00` - Explore MRI data with Nibabel and Nilearn
* `12:00-13:00` - Lunch
* `13:00-13:30` - How to set up your system, using Conda and Docker
* `13:30-15:00` - Functional connectivity and machine learning
* `15:00-15:30` - Innovations in neuroimaging tools (Part I)
* `15:30-...` - Open ended for questions

#### 10th November
* `09:30-10:00` - Introduction to Nipype
* `10:00-11:00` - Exploration of Nipype's building blocks
* `11:00-12:00` - Creating a Nipype Pipeline from A-Z
* `12:00-13:00` - Lunch
* `13:00-14:00` - PyBIDS and statistical analysis of fMRI data
* `14:00-15:00` - Multivariate pattern analysis using Searchlight and Deep Learning
* `15:00-15:30` - Innovations in neuroimaging tools (Part 2)
* `15:30-...` - Open ended for questions

\* While we include a short recap of Jupyter and Python, we won't be able to cover this section in details. So if you're new to them, please make sure to take a look at [this](https://nbviewer.jupyter.org/github/miykael/workshop_pybrain/blob/master/workshop/notebooks/01a_intro_jupyter-notebook.ipynb) and [this](https://nbviewer.jupyter.org/github/miykael/workshop_pybrain/blob/master/workshop/notebooks/01b_intro_python.ipynb) notebook before the session to familiarize yourself with these tools. Both notebooks can also be explored interactively within the Docker environment.

## 16-17 November 2020: M/EEG analysis with [MNE Python](https://mne.tools/stable/index.html)

*[Richard Höchenberger](https://hoechenberger.net/), INRIA Saclay, France*

[registration](https://www.eventbrite.co.uk/e/pybrain-meeg-analysis-with-mne-python-tickets-123244189689)

[instructions and materials](https://github.com/hoechenberger/pybrain_mne/)

The workshop will cover a broad range of topics to help you get to know all essential parts of MNE-Python for conducting MEG and EEG data analysis:

- loading, filtering, and inspecting raw data
- working with BIDS data
- epoching and artifact correction
- creating and visualizing evoked responses (ERP / ERF)
- contrasting evoked responses of different experimental conditions
- decoding neural responses (machine learning)
- performing time-frequency analysis
- estimating and visualizing cortical sources (source localization)
- conducting a group analysis

We will start with a **30 min warm-up at  9:00 a.m.** UTC on both days. During this warm-up, we can resolve technical difficulties you might be experiencing. **The actual workshop will start at 9:30.**

Lunch break is from 12 to 1, and we will continue until 3:30 or longer if need be (to hopefully address all open questions).

## 23-24 November 2020: Diffusion MRI with [DIPY](https://dipy.org/)

*[Rafael Henriques](https://github.com/rafaelnh), Champalimaud Centre for the Unknown, Lisbon, Portugal*

[registration](https://www.eventbrite.co.uk/e/pybrain-diffusion-mri-with-dipy-tickets-123245505625)

# Contact
[Johan Carlin](http://www.mrc-cbu.cam.ac.uk/people/Johan.Carlin/) (MRC CBU) for more details.
