# LoginApp with go and vuejs 


step 1
go mod init backend/main.go


step2
go get -u github.com/gin-gonic/gin
go get -u gorm.io/gorm
go get -u gorm.io/driver/mysql
go get -u github.com/joho/godotenv


step3 
go run main.go

/api/register 

{
    "username":"user",
    "password":"pass"
}

/api/login

{
    "username":"user",
    "password":"pass"
}


# frontend
npm install -g @vue/cli

vue create vue-frontend
npm install axios
vue add component Login
