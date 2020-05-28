1. npm install next react react-dom

2. in package.json:
"scripts": {
    "dev": "next"
  },

3. npm run dev

error : Error: > Couldn't find a `pages` directory. Please create one under the project root

4. so we will create a folder "pages" parallel to package.json
5. npm run dev : no error
    By fefault it runs on port 3000 , 

6. if we go to localhost:3000 
it will show 404 as nothing is there in "pages" folder

7. create a file index.js in "pages folder"
------------------------------------------
index.js
-------
 const Index = () =>  {
    return (
        <div>
            This is index page
        </div>
    )
}
export default Index;
------------------------------------------
refresh browser and we can see - This is index page
so initial setup is done
Note: with next js, hot loading is there 
====================================================================================================

