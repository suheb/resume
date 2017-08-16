### About
This theme is designed by Xiaoying Riley at 3rd Wave Media (http://themes.3rdwavemedia.com/). Visit her website for more themes [http://themes.3rdwavemedia.com/](http://themes.3rdwavemedia.com/)


[Sharath Kumar](https://www.youtube.com/embed/T2nx6tj-ZH4) have made this into a Jekyll theme [online-cv](https://github.com/sharu725/online-cv). This is the port for Pelican.

**Demo:** [https://suheb.in/resume](https://suheb.in/resume)

### Installation

The recommended way to install is over [pelican-themes](https://github.com/getpelican/pelican-themes).

Alternatively, to use this theme directly:
1. Clone this repo in any directory.
```
git clone https://github.com/suheb/resume.git
```
2. Edit your Pelican settings file (`pelicanconf.py`) to include this line:
```
THEME = "/path-to-directory/resume"
```

### Configuration

Add the following variables in your Pelican setting file.

Change these to add you own information to generate a personalised web resume.
```
#Profile information
NAME = 'Suhaib Khan'
TAGLINE = 'Full Stack Developer'
PIC = 'profile.png'

#sidebar links
EMAIL = 'suheb.work@gmail.com'
PHONE = '(+91) 9560038966'
WEBSITE = 'suheb.in'
LINKEDIN = 'suhebk'
GITHUB = 'suheb'
TWITTER = '@iamsuheb'

CAREER_SUMMARY = 'I am a full-stack developer currently working as a software developer at Zomato. I am a Google Summer of Code mentor for CLTK. I also participated in GSoC last year as a student. I have also worked at Aspiring Minds and various other startups mainly working on Web and Android.'

SKILLS = [
	{
		'title': 'JAVA',
   		'level': '90'
   	},
  	{
  		'title': 'Javascript &amp; jQuery',
   		'level': '95'
   	},
    {
  		'title': 'HTML5 &amp; CSS',
  		'level': '95'
  	},
  	{
  		'title': 'React',
  		'level': '90'
  	},
  	{
  		'title': 'PHP',
  		'level': '85'
  	}
]

PROJECT_INTRO = 'You can list your side projects or open source libraries in this section. '

PROJECTS = [
	{
		'title': 'Open Source Contributions',
		'tagline': 'Active contributor in FOSSASIA, worked on the Open Event project (both server and android app).Active contributor in CLTK, worked on the CLTK Web app and API.Made valuable contributions in phpBB, implemented a live search feature.Also made a few contributions to Processing.org and phpMyAdmin.'
	},
	{
		'title': 'Music Hub',
		'tagline': 'Android app that connects multiple devices via wifi and plays music in all connected devices simultaneously to create a loud stereo-like sound effect.'
	},
	{
		'title': 'Music Timer',
		'tagline': 'Android app that monitors phone’s movement to detect whether the user’s asleep and pause music playback accordingly.'
	}
]

LANGUAGES = [
	{
		'name': 'Hindi',
		'description': 'Native'
	},
	{
		'name': 'English',
		'description': 'Professional'
	},
	{
		'name': 'Urdu',
		'description': 'Amateur'
	}
]

INTERESTS = [
	'Gaming',
	'Cricket'
]

EXPERIENCES = [
	{
		'job_title': 'Software Development Engineer',
		'time': 'Oct 2016 - Present',
		'company': 'Zomato, Gurgaon IN',
		'details': 'Part of the web team working on developing a smart POS system for restaurants.'	
	},
	{
		'job_title': 'Web developer',
		'time': 'Aug 2016 - Dec 2016',
		'company': 'Archimedes Digital, WFH',
		'details': 'Worked on developing an online catalog for museums using scans of various objects (artifacts, books etc). Developed a highly zoomable image viewer and integrated linting and test suites to be used across projects.'
	},
	{
		'job_title': 'Google Summer of Code Student',
		'time': 'May 2016 - Aug 2016',
		'company': 'Classical Language Toolkit (CLTK), WFH',
		'details': 'Worked on the CLTK webapp - a modern reading environment to study classical languages. Updated the webapp to provide definitions, translations and commentary along with the text. Added functionality to add annotations and bookmarks to enhance the reading experience for user. Working on extending user profile to include annotations, bookmarks and other social networks.'	
	},
	{
		'job_title': 'Research and Development Intern',
		'time': 'May 2015 - June 2015',
		'company': 'Aspiring Minds, Gurgaon IN',
		'details': 'Developed a CRM-simulation module integrated into the employability assessment platform AMCAT. Created the frontend for the module and wrote backend code for question delivery and scoring. Designed the database schemas for the module compatible with the current platform’s database.'
	}
]

EDUCATIONS = [
	{
		'degree': 'B.E in Information Technology',
		'meta': 'Netaji Subhas Institute of Technology (NSIT)',
		'time': '2012 - 2016'
	},
	{
		'degree': 'High School',
		'meta': 'Ludlow Castle',
		'time': '2012'
	}
]
```

![resume theme](https://github.com/suheb/resume/raw/master/static/images/resume-theme.png)

The theme is responsive

![responsive resume theme](https://github.com/suheb/resume/raw/master/static/images/responsive-resume-theme.png)

There are 6 color schemes available:
Change the color theme by adding the following line to your pelican setting file:
```
CSS_FILE = 'main-1.css'
```

![resume theme](https://github.com/suheb/resume/raw/master/static/images/resume-theme-2.png)

Check out for more themes: [**Pelican Themes**](http://www.pelicanthemes.com)