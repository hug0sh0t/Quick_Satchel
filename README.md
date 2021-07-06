<a href="https://www.qsatchel.com/oauth/login">
<img  src="https://github.com/hug0sh0t/Quick_Satchel/blob/master/awesome.svg" width="80%" />
 </a>
 


New Application insert, along with endpoints for follow system 


## Deeper Details
Giving users the ability to see all the details of the Financial information they provide
with clear dynamic Data Driven visuals and Graphs 
# what problem does qsatchel solve? 
Many expense management systems that I have encountered in the market provide a surplus of what I need in terms of tracking my expenses.
Many of which are very time consuming when it comes to setup, and configuration of all my expenses. 
QuickSatchel is very easy to set up, and the User Interface that I created is very easy to use. 
Aside from the speed that Quick Satchel Provides, It also gives users the chance to visualize their expenses.


# How The Percentage Allocation Doughnut Engine was made

  
    for p in user_pockets: # user_pockets is the obj, holding the users pocket values
        absoluteSatchel += abs(p.price)
        if p.price >= 0:      
            positiveWeights.insert(0, (abs(p.price)/int(absoluteSatchel))*100)    
        else:
            negativeWeights.insert(0, (abs(p.price)/int(absoluteSatchel))*100)
     # Percentage Algorithm 
     dynamicPercentArray.insert(0, (abs(p.price)/int(absoluteSatchel))*100)

    for posW in positiveWeights:
        positiveWeightTotal += posW      # the postive percentage w/r to abs sum
    for negW in negativeWeights:
        negativeWeightTotal += negW      # the negative percentage w/r to abs sum


             

# Acknowledgements
The reason for including Third-Party Social Authentication, is to give users fastest route to becoming an authenticated member  
<br>   <a href="https://pypi.org/"> PYPI  foundation  </a>, 
and the <a href="https://www.chartjs.org/"> Chart JS javascript Library </a> played a huge role in the creation of this software
  
  <center class="mb-2" style="position:relative;margin-top:100px;color:grey"><small>©PocketSatchel 2021 <br><a
        style="text-decoration:none;color:grey" href='https://www.qsatchel.com/credits/'>
        Acknowledgments </a> | <a style="text-decoration:none;color:grey" href='https://www.qsatchel.com/qstermsofservice/'> 
        Terms and Conditions</a> | <a style="text-decoration:none;color:grey" href='https://www.qsatchel.com/privacypolicy/'> 
        Privacy Policy</a> 
        </small>

<small style="color:#c8c8c8"> You can try out this Live Application by pressing the Logo.
 Majority of the Directories have been moved to a Private Repository, as this is a Portfolio Project </small>
</center>
