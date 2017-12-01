Scripts for creating projects in GCP given a list of students) emails
Original source: https://medium.com/google-cloud/how-to-automate-project-creation-using-gcloud-4e71d9a70047
Summary of use from within the GCP Shell:
	-find your billing account id: gcloud alpha billing accounts list 0X0X0X-0X0X0X-0X0X0X
	-get the file itself: curl https://raw.githubusercontent.com/echancrure/gcp-scripts/master/create_projects.sh -o create_projects.sh
	-get executing rights: chmod +x create_projects.sh
	-run: ./create_projects.sh 0X0X0X-0X0X0X-0X0X0X c3itcarlow-20171201  somebody@gmail.com someother@gmail.com
Basic git commands
git status
git add .
git commit -m "commit message"
git push -f origin master
