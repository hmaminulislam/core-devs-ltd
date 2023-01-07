## Debug this app

### Live link
https://core-devs-ltd.netlify.app/

#### App had compile problem. Couldn't get the comingsoon component. I tried to import again but it was not importing. Later I entered the comingsoon file and saw that the file was not exported. I exported and capitalized the first letter of the component then imported.

#### The countdown was preceded by the "-" symbol. Because the end date was given as 2022. I do the date 2023.

#### Subscribe was calling the post api without validating the email. The match() method regular expression was previously against so the email validation was not working. I put the regular expression inside the match() method.