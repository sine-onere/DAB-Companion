# DAB-Companion - Design Doc

```
                      .*/((((((((((((((((((((((((((((((((((*.     
                    .*((##(((((((((((((((((((((((((((((##/,         Authored By Jesse Muniz
                 .*(##((((((((((((((((((((((((((((((##(*.     ,/*.  Reviewed By Nobody
              ,/(##((((((((((((((((((((((((((((((#((*.     .*(#(*.  Started on 8/29/2022
          .,/(((((((((((((((((((((((((((((((((#((/,.    .,/(##((*.  Finished in the future
       .*/(###(((((((((((#((((((((((((((((((#(/*.     ,/(#((((((*.       
       .......................................     .*/((((((((((*.       
                                                 ,/(((((((((((((*.       
  ,(###########((##(*    ,/(/////////////(/,   .,(##((((((((((((*.
  *#&&&&&&&&&&&&&&&%/    *################(*    ,((#((((((((((((, 
  *#%&%%%%%%%%%%%&&%/    *################(*    ,((#((((((((((((,
  *#%&%%%%%%%%%%%&&%/    *################(*    ,((#((((((((((((,
  *#%&%%%%%%%%%%%&&%/    *################(*    ,((#((((((((((((,
  *#%&%%%%%%%%%%%&&%/    *################(*    ,((#((((((((((((,
  *#%&%%%%%%%%%%%&&%/    *###############%#*    ,((#((((((((((((,
  *#%&%%%%%%%%%%%&&%/.   .,,,,,,,,,,,,,,,,,.    ,((#((((((((((((,
  *#%&%%%%%%%%%%&&#/.                           ,((#(((((((((#(/.
  *#%&%%%%%%%&&%(,     ,/(///////////////(/,    ,((#(((((((#(/,
  *#%&%%%%%%%#/.    ./#&&&&&&&&&&&&&&&&&&&%/    ,((#(((((##/,
  *#%&%%%%%(,.   .*(%&&%%%%%%%%%%%%%%%%%%&%/    ,((#(((#(/.
  *#%&%%#/.    ./#%&%%%%%%%%%%%%%%%%%%%%%&%/    ,((###(*.
  *#&%(,     ,(%&&%%%%%%%%%%%%%%%%%%%%%%%&%/    ,(##(*.
  *#/.    .*#%&%%%%%%%%%%%%%%%%%%%%%%%%%%&%/    ,((*.
        ,(%&%%%%%%%%%%%%%%%%%%%%%%%%%%%%%&%/   .,*.
      ,#%%###############################%#*
```

#

## Abstract
Draw a box companion app. A stopwatch app that helps people track time spent studying vs play. Intended to make Draw A Box easier to track the 50% rule for play and practice.

#

## Objective
DAB-Companion will clearly show the play time, practice time, any imbalance and the history of all of it.

1. Timer for current session
2. Button for play and practice
3. Log of play, log of practice including dates
4. Display of the logs
5. Hours spent for each side
6. Display of imbalance of time
7. Warmup generator with included timer
8. Support for any platform
    
#

## Out of Scope Pitfalls

1. Simplistic GUI, Nothing special
2. Must not require internet
3. Should not require special packages
4. Using anything but javascript, css, html

#

## Design Highlights

### Phase 1
Build basic timer app to learn javascript fundementals. (M1)

### Phase 2
Add design features to build out DAB to full scope of the app except history. (M2, M3)

### Phase 3
Create pertinance by adding the log files (M4)

### Phase 4
Polish app to release state and subject myself to criticism. (M5)

#

## Milestones

### Build a timer with rudimentary GUI - M1
- Est. 2 hours

### Build wireframe diagram - M2
- Est. 1 hours
  
### Build GUI to wireframe design - M3
- Est. 16 hours

### Establish Ability to write/read log files - M4
- Est. 4 hours

### Convert to all platform support. Build electron app and flutter app - M5
- Est. 24 hours (No experience here)

#

## References - APA Citation

Babich, N., &amp; Morales, J. (2020, April 22). Design documentation. Ideas. Retrieved August 6, 2022, from https://xd.adobe.com/ideas/principles/web-design/design-documentation/ 

Google. (n.d.). Design Documents. Design documents. Retrieved August 6, 2022, from https://www.chromium.org/chromium-os/chromiumos-design-docs/ 

Ludicchart. (2020, November 18). How to create software design documents. Lucidchart TechBlog. Retrieved August 6, 2022, from https://www.lucidchart.com/blog/how-to-create-software-design-documents 

Zhang, A. (2018, June 8). How to write a good software design doc. #SOFTWARE DEVELOPMENT. Retrieved August 6, 2022, from https://www.freecodecamp.org/news/how-to-write-a-good-software-design-document-66fcf019569c/ 