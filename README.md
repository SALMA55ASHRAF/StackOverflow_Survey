# StackOverflow_Survey
Hello,every one that one of dataset on stack overflow annual developer survey dataset of 2020 this dataset was csv file it consist of 61 columns (features)
and 64461 rows.
first i start clean the data by dropping all NaN Values by dropna() function 
then the shape of data become 4213 rows , then start search if there any duplicates to drop it but there was no duplicates .
now our data is ready i start to understand data  features to have basic knowledge of it and what i have understand was :
MainBranch:  Which of the following options best describes you today? Here, by "developer" we mean "someone who writes code."
Hobbyist:  Do you code as a hobby?
Age:  What is your age (in years)? If you prefer not to answer, you may leave this question blank.
Age1stCode:  At what age did you write your first line of code or program? 
CompFreq:  Is that compensation weekly, monthly, or yearly?
CompTotal:  What is your current total compensation (salary, bonuses, and perks, before taxes and deductions), in `CurrencySymbol`? Please enter a whole number in the box below, without any punctuation. If you are paid hourly, please estimate an equivalent weekly, monthly, or yearly salary. If you prefer not to answer, please leave the box empty.
ConvertedComp:  Salary converted to annual USD salaries using the exchange rate on 2020-02-19, assuming 12 working months and 50 working weeks.
Country:  Where do you live?
CurrencyDesc:  Which currency do you use day-to-day? If your answer is complicated, please pick the one you're most comfortable estimating in.
CurrencySymbol:  Which currency do you use day-to-day? If your answer is complicated, please pick the one you're most comfortable estimating in.
DatabaseDesireNextYear:  Which database environments have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the database and want to continue to do so, please check both boxes in that row.)
DatabaseWorkedWith:  Which database environments have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the database and want to continue to do so, please check both boxes in that row.)
DevType:  Which of the following describe you? Please select all that apply.
EdLevel:  Which of the following best describes the highest level of formal education that you’ve completed?
Employment:  Which of the following best describes your current employment status?
Ethnicity:  Which of the following describe you, if any? Please check all that apply. If you prefer not to answer, you may leave this question blank.
Gender:  Which of the following describe you, if any? Please check all that apply. If you prefer not to answer, you may leave this question blank.
JobFactors:  Imagine that you are deciding between two job offers with the same compensation, benefits, and location. Of the following factors, which 3 are MOST important to you?
JobSat:  How satisfied are you with your current job? (If you work multiple jobs, answer for the one you spend the most hours on.)
JobSeek:  Which of the following best describes your current job-seeking status?
LanguageDesireNextYear:  Which programming, scripting, and markup languages have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the language and want to continue to do so, please check both boxes in that row.)
LanguageWorkedWith:  Which programming, scripting, and markup languages have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the language and want to continue to do so, please check both boxes in that row.)
MiscTechDesireNextYear:  Which other frameworks, libraries, and tools have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the framework and want to continue to do so, please check both boxes in that row.)
MiscTechWorkedWith:  Which other frameworks, libraries, and tools have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the framework and want to continue to do so, please check both boxes in that row.)
NEWCollabToolsDesireNextYear:  Which collaboration tools have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you worked with the tool and want to continue to do so, please check both boxes in that row.)
NEWCollabToolsWorkedWith:  Which collaboration tools have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you worked with the tool and want to continue to do so, please check both boxes in that row.)
NEWDevOps:  Does your company have a dedicated DevOps person?
NEWDevOpsImpt:  How important is the practice of DevOps to scaling software development?
NEWEdImpt:  How important is a formal education, such as a university degree in computer science, to your career?
NEWJobHunt:  In general, what drives you to look for a new job? Select all that apply.
NEWJobHuntResearch:  When job searching, how do you learn more about a company? Select all that apply.
NEWLearn:  How frequently do you learn a new language or framework?
NEWOffTopic:  Do you think Stack Overflow should relax restrictions on what is considered “off-topic”?
NEWOnboardGood:  Do you think your company has a good onboarding process? (By onboarding, we mean the structured process of getting you settled in to your new role at a company)
NEWOtherComms:  Are you a member of any other online developer communities?
NEWOvertime:  How often do you work overtime or beyond the formal time expectation of your job?
NEWPurchaseResearch:  When buying a new tool or software, how do you discover and research available solutions? Select all that apply.
NEWPurpleLink:  You search for a coding solution online and the first result link is purple because you already visited it. How do you feel?
NEWSOSites:  Which of the following Stack Overflow sites have you visited? Select all that apply.
NEWStuck:  What do you do when you get stuck on a problem? Select all that apply.
OpSys:  What is the primary operating system in which you work?
OrgSize:  Approximately how many people are employed by the company or organization you currently work for?
PlatformDesireNextYear:  Which platforms have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the platform and want to continue to do so, please check both boxes in that row.)
PlatformWorkedWith:  Which platforms have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the platform and want to continue to do so, please check both boxes in that row.)
PurchaseWhat:  What level of influence do you, personally, have over new technology purchases at your organization?
Sexuality:  Which of the following describe you, if any? Please check all that apply. If you prefer not to answer, you may leave this question blank.
SOAccount:  Do you have a Stack Overflow account?
SOComm:  Do you consider yourself a member of the Stack Overflow community?
SOPartFreq:  How frequently would you say you participate in Q&A on Stack Overflow? By participate we mean ask, answer, vote for, or comment on questions.
SOVisitFreq:  How frequently would you say you visit Stack Overflow?
SurveyEase:  How easy or difficult was this survey to complete?
SurveyLength:  How do you feel about the length of the survey this year?
Trans:  Are you transgender?
UndergradMajor:  What was your primary field of study?
WebframeDesireNextYear:  Which web frameworks have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the framework and want to continue to do so, please check both boxes in that row.)
WebframeWorkedWith:  Which web frameworks have you done extensive development work in over the past year, and which do you want to work in over the next year? (If you both worked with the framework and want to continue to do so, please check both boxes in that row.)
WelcomeChange:  Compared to last year, how welcome do you feel on Stack Overflow?
WorkWeekHrs:  On average, how many hours per week do you work? Please enter a whole number in the box.
YearsCode:  Including any education, how many years have you been coding in total?
that was our columns with there meaning then i start analysis these row by value_counts() function :
most of people on stack overflow codding as hoppy , developer by profession,most of them aged 24 to 32 years old 
first time they start coding was in ages between 10 to 18 years old and most was at age of 12 years old 
most database was used is Microsoft sql server 
most gender are male 👨
most of them have Bachelors
most of them from fullstack 
most of them using programming languages as (c#,html/css,JavaScript,sql,typescript)
if they are employed so they are working full-time ⌚
most of people from European decent
most of them not searching for job but available for any new opportunities
the employee are very satisfied with their job and if they have work than one job there answer based on the jo they spent most of time in it 
most of them working on windows and Microsoft azure as platforms
most of them working on framework as node.js
most of there company's  doesn't have dectied  devops person
most of them learn new framework or library once ayear or every few months 
most of them have experience in coding from 6 to 20 years 
most of them was coding like pro from 2 to 10 years experience.
that was i have learned from dataset hope its helpful for all of you 
wish to get better step by step 
#data analysis
#python



