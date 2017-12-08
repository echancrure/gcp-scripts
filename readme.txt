Scripts for creating projects in GCP given a list of students) emails
Original source: https://medium.com/google-cloud/how-to-automate-project-creation-using-gcloud-4e71d9a70047
Summary of use from within the GCP Shell:
	-find your billing account id: gcloud alpha billing accounts list 0X0X0X-0X0X0X-0X0X0X
	-get the file itself: curl https://raw.githubusercontent.com/echancrure/gcp-scripts/master/create_projects.sh -o create_projects.sh
	-get executing rights: chmod +x create_projects.sh
	-run: ./create_projects.sh 0X0X0X-0X0X0X-0X0X0X project-prefix  somebody@gmail.com someother@gmail.com
TODO
remove the alpha: use gcloud projects directly
I have not tested the delete script
project-prefix should be unique to you, in lower case. Suggest adding creating date at the end e.g. itcarlow-20171208
the script should be improved to ensure lower cases in project ids  

	
Basic git commands
git status
git add .
git commit -m "commit message"
git push -f origin master
