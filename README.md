# FunMappOne

---

## 💻 Installation (from GitHub)

1. **Get "remotes" package**:
  
   ```r
   install.packages("remotes")
   ```
   
2. **Install the package from GitHub**:
   
   ```r
   remotes::install_github(repo="fhaive/FunMappOnePackage")
   ```
   
## 💻 Installation (build local)
1. **Create tar.gz file**:  

   ```r
   devtools::build()
   ```

2. **Install the package**:
   ```r
   install.packages("path_to_the_tar.gz.file", type = "source", repos = NULL)
   ```
   
