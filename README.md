# Creating-own-R-Markdown-File
Open GitHub and create a new repository
Open R studio 
> Go to New File > R Markdown >  
      Give a title to it > select HTML as a default output and save the file.
 Click on Knit button > select knit to HTML( you can also select knit to pdf or word ) - It will ask you to save the file in html format > save the file >
 
 We can insert R code chunks, plots, tales etc.. in the R markdown file.
 
 Insert R codechunks in the R markdown file by using the code below.
           ```{r cars}
           summary(cars)
           ```
              
 We can also embed plots. For example
         ```{r pressure, echo=FALSE}
         plot(pressure)
         ```
     
