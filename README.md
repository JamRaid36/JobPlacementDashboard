# Live Project
## Introduction
I recently did my first live project with the Tech Academy for the Software Developer Bootcamp. I was given the opportunity to do a two  week sprint with a team of instructors and peers. We continued work on an ongoing project creating apps designed to take advantage of various Python and Django features. Within the scope of this project we created databases to keep track of data, implemented CRUD functionality and interacted with APIs to retrieve and save data. This project was built utilizing Python, Django, SQLite, and HTML/CSS. This was my first opportunity to work with a tech team in a profesional environment and it was very exciting. I was able to complete both [front end stories](#front-end-stories) and [back end stories](#back-end-stories) as well as being able to gain and work with some valuable project management [skills](#other-skills-learned) that I'm sure will come in handy in the future. Below are a few of the stories I completed during this project.

## Front End Stories
  - [Build The Basic App](#build-the-basic-app)
  - [Front End Imporovements](#front-end-improvements)

### Build the Basic App
For this story I had to create an app using the Django framework that could track my hobby data as well as displaying a home page with basic content. This included a Navbar, Background, Title and Footer. This would be the base of every page for the project
![WorldOfSitcoms](https://user-images.githubusercontent.com/105257619/193344775-78d096ef-8e99-4390-a049-5e723f6ec4e8.png)

### Front End Improvements
This was basic front end improvement to the UI/UX. I went throu and tried to and changed color schemes, altered button placement and form sizes to my liking and make sure things were consistent from page to page!
```
/* Basic Styling */

* {
    margin: 0;
}

html {
    background-color: lightblue;
}

body {
	position: relative;
	overflow: hidden;
}
html, body {
    height: 100%;
    margin: 0;
	padding: 0;
}
p {
	padding: 4px 16px;
	font-size: 20px;
	font-family: 'Lato', Georgia, sans-serif;
	color: #666666;
}

h1 {
    color: white;
    font-family: 'Lobster';
    font-size: 35px;
    text-shadow: 3px 2px 1px gray;
    margin:15px auto;
    text-align: center;
}
h2 {
    color: #213e4a;
    font-weight: 900;
    font-family: 'Roboto', sans-serif;
    text-align: center;
}
h2 span {
    font-variant: small-caps;
    padding: 2px 16px;
}
h3 {
    color: black;
    font-weight: 900;
    font-family: 'Roboto', sans-serif;
    text-align: center;
    font-size: 25px;
}
h3 span {
    font-variant: small-caps;
    padding: 2px 16px;
}

h4 {
    padding: 4px 16px;
	font-size: 15px;
	font-family: 'Lato', Georgia, sans-serif;
	color: #666666;
	text-align: center;
}

th {
    font-size: 20px;
    color: black;
}

td {
    font-size: 20px;
    color: black;
}

a {
    color: black;
}



/* End Basic Styling */
/* Background and Image Styling */

.bg_img {
    background-color: lightblue;
    background-image: url('/static/images/sitcoms_image.jpg');
    background-size: cover;
    background-attachment:fixed;
    background-position: center;
    position: relative;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}
/* End Background and Image Styling */
/* Form Styling */
.admin_panel {
    position: relative;
    top: 1px;
    margin: 0 auto;
    width: 50%;
    height: 50%;
    background-color: #fffaf4;
	border: 1px solid #d6d6d6;
	box-shadow: 0 1px 2px rgba(0,0,0,0.15);
	transition: all 0.3s ease-in-out;
	border-radius: 10px;
    transition: 0.3s;
}

.admin_panel:hover {
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
	transition: opacity 0.3s ease-in-out;
}

.center {/* centers table on read page */
  margin-left: auto;
  margin-right: auto;
}

th {/* centers table on read page */
    text-align: left;
}

table {/* adds space between columns */
  border-collapse: separate;
  border-spacing: 30px 30px;
}
input, textarea {
    width: 100%;
    margin: 1% 0 0 0;
    padding: 1% 0 2% 1%;
    line-height: 18px;
    font-size: 15px;
    border-radius: 5px;
    border: 2px solid silver;
}
label {
	display: inline-block;
    width: 95%;
    text-align: left;
    margin: 1% 0 0 0;
    color: black;
    line-height: 18px;
    font-size: 20px;
}
input[type="submit"]:hover {
    background-color: #355664;
    color: white;
    border: 2px solid #b3b3b3;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
	transition: opacity 0.3s ease-in-out;
}

input, textarea {
    width: 100%;
    margin: 1% 0 0 0;
    padding: 1% 0 2% 1%;
    line-height: 18px;
    font-size: 15px;
    border-radius: 5px;
    border: 2px solid silver;
}
label {
	display: inline-block;
    width: 95%;
    text-align: left;
    margin: 1% 0 0 0;
    color: black;
    line-height: 18px;
    font-size: 20px;
}

/* form item container */
.frmObject_container {
	display: block;
    width: 80%;
    margin: 0 auto;
    padding: 0;
    text-align: center;
}
/* End Form Styling */
/* form button container */
.frmBtn_container {
    margin: auto;
    position: relative;
    justify-content: space-evenly;
    display: flex;
    flex-wrap: wrap;
    width: 100px;
    height: 50px;
}
.btn {
	flex-grow: 1;
    justify-content: center;
    text-align: center;
    display: inline-block;
    width: 25%; /* button size */
    margin: 2% 2% 2% 2%;
    color: black;
    padding: 5px 0px;
    text-decoration: none;
    font-size: 14px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
    border: 2px solid silver;
    border-radius: 5px;
}

.btn:hover{
    background-color: #355664;
    text-decoration: none;
    color: white;
    border: 2px solid silver;
    box-shadow: 0 0px 0px rgba(0,0,0,0.3);
	transition: opacity 0.3s ease-in-out;
}
/* End form button container */
```

## Back End Stories
  - [Details Page](#details-page)
  - [Connect to and Parse through API](#connect-to-and-parse-through-api)

### Details Page
For these stories I was tasked with displaying the description for items I had previosuly added to the database and then also being able to edit the data associted ith these items. These are functions I employed to render and enable editing features for the app.
```
# Story #4: Details page -----------------------------------------------------------------------------------------------


def sitcom_details(request, pk):
    sitcom = get_object_or_404(Sitcom, pk=pk)
    content = {'sitcom': sitcom}
    return render(request, 'Sitcoms/sitcoms_details.html', content)

# Story #5: Edit and Delete Functions ----------------------------------------------------------------------------------


def sitcom_update(request, pk):
    sitcom = get_object_or_404(Sitcom, pk=pk)
    form = SitcomForm(data=request.POST or None, instance=sitcom)
    if request.method == 'POST':
        if form.is_valid():
            form.save()
            return redirect('../../read')
    content = {'form': form, 'sitcom': sitcom}
    return render(request, 'Sitcoms/sitcoms_update.html', content)
```
### Connect to and Parse through API
For these two stories I had to find an API that I wanted to use, connect to it and parse through the correct data I wanted to display.

```
# Story #6-(API Pt 1): Connect to API ----------------------------------------------------------------------------------
# Story #7-(API Pt 2): Parse through JSON

def sitcom_api(request):
    url = "https://yahoo-weather5.p.rapidapi.com/weather"

    querystring = {"location": "longview,wa", "format": "json", "u": "f"}

    headers = {
        "X-RapidAPI-Key": "1ba8d27b19mshd71557ea88643ebp14a569jsnc81e62fac8f7",
        "X-RapidAPI-Host": "yahoo-weather5.p.rapidapi.com"
    }

    response = requests.request("GET", url, headers=headers, params=querystring)

    api_info = json.loads(response.text)
    temp_int = api_info["current_observation"]["condition"]["temperature"]
    current_temperature = str(api_info["current_observation"]["condition"]["temperature"]) + ' \N{DEGREE SIGN}F'
    content = {"current_temperature": current_temperature, "temp_int": temp_int}
    return render(request, 'Sitcoms/sitcoms_api.html', content)
```
## Other Skills Learned
 - Worked with a team and was able to glean from their work as well as interact with the leads when I hit a snag that I couldn't solve.
 - Learning and utilizing good version control practices through git bash and Pycharm. 
 	- This enabled me to revert to previous points in my project when needed as well debug without negatively influencing others hard work.
 - Due to being in this program while working another job and managing a side business, I was really able to hone my own time management skills which I feel is crucial to any professional career, especially in the tech industry.

Jump to: [Front End Stories](#front-end-stories), [Back End Stories](#back-end-stories), [Other Skills Learned](#other-skills-learned), [Page Top](#introduction)
