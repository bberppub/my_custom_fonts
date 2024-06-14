## mycustomfonts

Change All the fonts(google or not) to local Source Han Sans
Tested on Frappe/ERPNext v14 & v15

## Steps

1. cd {your workspace folder}
2. git clone https://github.com/bberppub/my_custom_fonts.git --branch=develop
3. Switch to your {bench folder}
4. bench get-app {the app folder you have cloned in step3}
5. bench install-app my_custom_fonts
6. bench setup requirements
7. bench migrate
8. Restart the service && clear cache


#### License

mit
