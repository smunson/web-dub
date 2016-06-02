---
################################################################################
# Version of the people format. The only valid value for this is 1. 
# We may increment this in the future to simplify maintenance of old people.
################################################################################
version: 1

################################################################################
# A people file might exist but lack values for some fields. These are 'NA'. 
# The only valid value is 'True'. A NA field should not be present if 'False'.
################################################################################
na_web: true

################################################################################
# Full name listed in the order of last name, first name, middle name(s).
#
# name: 
# - Surname
# - First
# - Middle
# - More
################################################################################
name:
- Ko
- Andrew
- J.

################################################################################
# Each person has a single main role, and may have additional alumni roles.
# The first role that is listed is their main (current) role.
# Valid roles: faculty, doctoral, masters, undergrad, staff
#              alumni-faculty, alumni-doctoral, alumni-masters, alumni-undergrad
#
# A person may have multiple positions. Positions consist of titles and units.
# Each value for a field must match one of the options below exactly.
#
# Valid faculty titles: Professor, Professor Emeritus
#
# Valid faculty and doctoral units:
#   Computer Science & Engineering
#   Division of Design
#   Human Centered Design & Engineering
#   Information School
#   Human Computer Interaction & Design
#   Architecture
#   Biomedical & Health Informatics
#   Communications
#   DXARTS Digital Arts
#   Electrical Engineering
#   Industrial & Systems Engineering
#   Mechanical Engineering
#   Psychology
# 
# Valid masters units:
#   Master of Science in Computer Science & Engineering
#   Master of Design
#   Master of Science in Human Centered Design & Engineering
#   Master of Science in Information Management
#   Master of Library and Information Science
#   Master of Human-Computer Interaction + Design
#   Master of Science in Architecture
#   Master of Science in Biomedical and Health Informatics
#   Master of Communication in Digital Media
#   Master of Communication in Communities and Networks
#   Master of Science in Electrical Engineering
#   Master of Industrial and Systems Engineering
#   Master of Science in Industrial Engineering
#   Master of Science in Mechanical Engineering
#   Master of Science in Engineering
#
# Faculty have one or more title and units.
# role:
#  - faculty
# position:
#  - title: Professor
#    unit: Information School
#  - title: Professor
#    unit: Computer Science & Engineering
# 
# Students do not have a title, but can have one more units.
#
# For a doctoral student their unit is the name of their department.
# role:
#  - doctoral-student
# position:
#  - unit: Information School
#
# For a master's student their unit is the name of their program.
#  role:
#  - masters-student
#  position:
#  - unit: Master of Science in Human Centered Design & Engineering
#
################################################################################
role:
- faculty

position:
- title: Associate Professor
  unit: Information School
- title: Adjunct Associate Professor
  unit: Computer Science & Engineering

################################################################################
# A person may have a website. If not, this field should not be present.
#
# web:
# - http://faculty.washington.edu/ajko/
################################################################################
web:
- http://faculty.washington.edu/ajko/

############################################################
# These fields are provided to ease migration of old content.
# They are not used, and should be deleted when no longer desired.
old-dub-bio: Andrew Ko is an Assistant Professor at the <a href="http://ischool.uw.edu/">Information
  School</a> at the <a href="http://www.washington.edu">University of Washington</a>.
  His research interests include human and cooperative aspects of software development
  and design, and more broadly, the fields of human-computer interaction and software
  engineering. He has published articles in all of these areas, receiving best paper
  awards at top conferences such as the <a href="http://www.icse-conferences.org/">International
  Conference on Software Engineering</a> (ICSE) and the <a href="http://www.chi2007.org">ACM
  Conference on Human Factors in Computing</a> (CHI), as well as extensive press on
  the <a href="http://faculty.washington.edu/ajko/whyline-java.shtml">Whyline</a>,
  a debugging tool that lets users ask why questions about problematic output. In
  2010, he was awarded an NSF CAREER award to support his research and teaching on
  evidence-based bug triage. In 2004, he was awarded both <a href="http://www.nsf.gov/grfp">NSF</a>
  and <a href="http://www.asee.org/ndseg">NDSEG</a> research fellowships in support
  of his Ph.D. research. He received his Ph.D at the <a href="http://www.hcii.cs.cmu.edu">Human-Computer
  Interaction Institute</a> at <a href="http://www.cmu.edu">Carnegie Mellon University</a>,
  advised by <a href="http://www.cs.cmu.edu/~bam">Brad Myers</a>. He received Honors
  Bachelors of Science degrees in Computer Science and Psychology from <a href="http://www.oregonstate.edu">Oregon
  State University</a> in 2002.
old-dub-photo: icons/people/mug_1.jpg
twitter:
- andyjko
---