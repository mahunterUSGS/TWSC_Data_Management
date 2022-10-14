---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
venue: "U.S. Geological Survey"        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: "online"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "US"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "EN"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the workshop
latitude: "35.19894"        # decimal latitude of workshop venue (use https://www.latlong.net/)
longitude: "-111.64932"       # decimal longitude of the workshop venue (use https://www.latlong.net)
humandate: "June 16, 2022"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "8:00 am - 3:30 pm PDT (11:00 am - 6:30 pm EDT)"    # human-readable times for the workshop e.g., "8:00 am - 3:30 pm CEST (8:00 am - 3:30 pm UTC)"
startdate: 2022-06-16      # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2022-06-16        # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
instructor: ["Marc Hunter","Madison Langseth"] # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper: ["Christopher Sherwood","Brandon Serna","Amber Jones"]     # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["mahunter@usgs.gov","mlangseth@usgsg.gov"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
collaborative_notes:  "https://doimspp-my.sharepoint.com/:w:/g/personal/mahunter_usgs_gov/EQb5KbLNn49OmzUTRKB6QtUBiYN9SDOcwVNgGMEnUWDsjg?e=Iwxkm5" # optional: URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite: "https://doimspp-my.sharepoint.com/:w:/g/personal/mahunter_usgs_gov/EQb5KbLNn49OmzUTRKB6QtUBiYN9SDOcwVNgGMEnUWDsjg?e=Iwxkm5"          # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---

{% comment %} See instructions in the comments below for how to edit specific sections of this workshop template. {% endcomment %}

{% comment %}
HEADER

Edit the values in the block above to be appropriate for your workshop.
If the value is not 'true', 'false', 'null', or a number, please use
double quotation marks around the value, unless specified otherwise.
And run 'make workshop-check' *before* committing to make sure that changes are good.
{% endcomment %}


{% comment %}
8< ============= For a workshop delete from here =============

8< ============================= until here ==================
{% endcomment %}


{% comment %}
Check DC curriculum
{% endcomment %}

{% if site.carpentry == "dc" %}
{% unless site.curriculum == "dc-astronomy" or site.curriculum == "dc-ecology" or site.curriculum == "dc-genomics" or site.curriculum == "dc-socsci" or site.curriculum == "dc-geospatial" %}
<div class="alert alert-warning">
It looks like you are setting up a website for a Data Carpentry curriculum but you haven't specified the curriculum type in the <code>_config.yml</code> file (current value in <code>_config.yml</code>: "<strong>{{ site.curriculum }}</strong>", possible values: <code>dc-astronomy</code>, <code>dc-ecology</code>, <code>dc-genomics</code>, <code>dc-socsci</code>, or <code>dc-geospatial</code>). After editing this file, you need to run <code>make serve</code> again to see the changes reflected.
</div>
{% endunless %}
{% endif %}

{% comment %}
Check SWC curriculum
{% endcomment %}

{% if site.carpentry == "swc" %}
{% unless site.curriculum == "swc-inflammation" or site.curriculum == "swc-gapminder" %}
<div class="alert alert-warning">
It looks like you are setting up a website for a Software Carpentry curriculum but you haven't specified the curriculum type in the <code>_config.yml</code> file (current value in <code>_config.yml</code>: "<strong>{{ site.curriculum }}</strong>", possible values: <code>swc-inflammation</code>, or <code>swc-gapminder</code>). After editing this file, you need to run <code>make serve</code> again to see the changes reflected.
</div>
{% endunless %}
{% endif %}

<h2>Day 1</h2>
<h3>Date and Time TBD</h3>
<div class="row">        <!-- first two days -->
  <div class="col-md-6"> <!-- left column -->
    <table class="table table-striped">
      <tr>               <!-- row 1   -->
        <td></td>
        <td>Before starting</td>
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management/blob/main/LESSONS/Data_Links.md" target="_blank">Software Requirements and Exercise Data</a></td>
      </tr>
      <tr>               <!-- row 21   -->
        <td>08:00</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Introduction</a></td>
        <td>Meet your instructors and review Code of Conduct</td><!-- content -->
      </tr>
      <tr>               <!-- row 2   -->
        <td>08:15</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Governing Policies and Directives</a></td>        <!-- content -->
        <td>What are the rules and what are my responsibilities when funded?</td>        <!-- content -->
      </tr>
      <tr>               <!-- row 3   -->
        <td>09:15</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">FAIR Data</a></td>        <!-- content -->
        <td>How FAIR data principles support a realized PDE, data in support of science research, life cycle of data</td>        <!-- content -->
      </tr>
      <tr>               <!-- row 19   -->
        <td>10:30</td>        <!-- time    -->
        <td>Morning coffee</td>
        <td>Break</td>
      </tr>
      <tr>               <!-- row 4   -->
        <td>10:45</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Metadata and unique identifiers</a></td>        <!-- content -->
        <td>Options for long-term repositories, unique identifiers, tools for metadata</td>
      </tr>
      <tr>               <!-- row 11   -->
        <td>12:00</td>        <!-- time    -->
        <td>Lunch</td>
        <td>Break</td>            <!-- content -->
      </tr>
      <tr>               <!-- row 5   -->
        <td>12:45</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Data organization and formatting</a></td>        <!-- content -->
        <td>Best practices for the organization of common data types, introduction to TIDY data principles</td>
      </tr>
      <tr>               <!-- row 11   -->
        <td>2:00</td>        <!-- time    -->
        <td>Afternoon coffee</td>
        <td>Break</td>            <!-- content -->
      </tr>
      <tr>
        <td>2:15</td>
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Tips to automate large volumes</a></td>
        <td>How do I handle large volumes of similar information?</td>
      <tr>
        <td>3:30</td>
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Review and questions</a></td>
        <td>How do these pieces work together?</td>
      </tr>
      </tr>
        <td>4:00</td>        <!-- time    -->
        <td>Finish</td>
        <td></td><!-- content -->
      </tr>
    </table>
  </div>
</div>
<h2>Day 2</h2>
<h3>Date and Time TBD</h3>
<div>
  <div>
    <table>
      <tr>               <!-- row 8   -->
        <td>08:00</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Data organization exercises</a></td>
        <td>How do we organize common data formats?</td>         <!-- content -->
      </tr>
      <tr>               <!-- row 9   -->
        <td>09:00</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Format conversion exercises</a></td>
        <td>How do we translate data into different formats?</td>             <!-- content -->
      </tr>
      <tr>               <!-- row 10   -->
        <td>10:00</td>        <!-- time    -->
        <td>Morning coffee</td>
        <td>Break</td>
      </tr>
      <tr>               <!-- row 12   -->
        <td>10:15</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Metadata exercises</a></td>
        <td>Creating standard-compliant metadata using open tools</td>           <!-- content -->
      </tr>
      <tr>               <!-- row 13   -->
        <td>11:30</td>        <!-- time    -->
        <td>Lunch</td>
        <td>Break</td>         <!-- content -->
      </tr>
      <tr>               <!-- row 14   -->
        <td>12:15</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Data and metadata reviews</a></td>
        <td>Best practices to review scientific data and metadata</td>           <!-- content -->
      </tr>
      <tr>               <!-- row 15   -->
        <td>1:30</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Archiving data</a></td>
        <td>How to submit archives for common digital repositories</td>          <!-- content -->
      </tr>
      <tr>               <!-- row 16   -->
        <td>2:30</td>        <!-- time    -->
        <td>Afternoon Coffee</td>
        <td>Break</td><!-- content -->
      </tr>
      <tr>               <!-- row 17   -->
        <td>2:45</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Indexing data with data.nasa.gov</a></td>
        <td>What are the options and methods?</td><!-- content -->
      </tr>
      <tr>               <!-- row 18   -->
        <td>3:30</td>        <!-- time    -->
        <td><a href="https://github.com/mahunterUSGS/TWSC_Data_Management">Review and questions</a></td>
        <td>What resources are available to use and keep up with current efforts?</td>
      </tr>
        <td>4:00</td>        <!-- time    -->
        <td>Finish</td>
        <td></td><!-- content -->
      </tr>
    </table>
  </div>
</div>
