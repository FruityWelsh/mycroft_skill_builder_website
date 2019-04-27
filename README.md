# mycroft_skill_builder_website
A webpage to simplfy building mycroft skills

Breakdown:

 * Name and description section
 * Interactive Table
 * Generated Code page

Name and description:
This is just a section for you name your skill add authors, and write the readme

Interactive Table:
This is a table that is built in a message response way. So you can create a converstion where you ask one thing, and mycroft does somethings, and can ask you a question, you respond etc. For APIs outside of mycrofts scope, create a extra collium for responses from them.

Example:
<pre>
User                  Mycroft                      Weather_service.com
Hey mycroft
                      *Activates
                      *Beeps
Whats the weather like?
                      Let me see
                      *Checks settings for API
                      *Run weather_api_check_current
                                                   Returns JSON for weather
                      *Speak weather_json.value
                      *Wait for talking
                      Is there anything else you like?
                      *if ~yes proccess else exit
</pre>

Generate Code page:
Shows the generated python code and give options to upload to the skill repo, personal repo, or just download
                         

