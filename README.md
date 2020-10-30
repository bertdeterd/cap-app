# Getting Started


cds init

 "cds": {
    "hana" : { "deploy-format": "hdbtable" },
    "requires": {
      "db": {
        "kind": "sql"
      }
    }
  }


  cds add mta

  npm install


  db/schema.cds

 install vscode extensie cds cap

 cds watch

 npm add sqlite3 -D
cds deploy --to sqlite:my.db

add files

npm add @sap/hana-client --save


https://help.sap.com/viewer/e54136ab6a4a43e6a370265bf0a2d744/latest/en-US/c049e28431ee4e8280cd6f5d1a8937d8.html
sapcar -xvf SAPCRYPTOLIBP_8535-20011729.SAR


cds deploy --to hana

cf push -f gen/srv --random-route


{
    "authenticationMethod":"route",
    "routes": [
        {
            "source": "^/(.*)$",
            "target": "$1",
            "authenticationType": "xsuaa",
            "destination": "srv_api",           
            "csrfProtection": false
            
        }
    ]
}

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
