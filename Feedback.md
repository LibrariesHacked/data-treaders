## Feedback 

We wanted to know what people thought of Library Data Day, to find out which sessions attendees got the most out of and to see how our outcomes were met. 

All attendees were sent a link to a [Google form](https://goo.gl/forms/5JSfERpKy2omwleI2) asking for feedback. 

#### Which sessions did you attend that you personally got the most out of?

Library Data Camp was mostly run as an unconference, so many sessions were decided on the day. We thought it would be useful to know which sessions attendees got the most out of personally. 

{% chartjs %} 
{ 
  type: 'bar', 
  data: { 
  labels: ["Data Intro", "Open Data 101", "Open Data advocacy", "Extracting data", "Core dataset/schema","Social media", "OpenRefine","Text adventures", "API", "Publish your first dataset", "Social value", "Open Data Camp", "Command Line", "SQL"], datasets: [{ 
    label: '# of Votes', 
    data: [3, 8, 2, 1, 1, 2, 3, 2, 4, 4, 2, 1], 
    backgroundColor: [ 
      'rgba(255, 99, 132, 0.2)', 
      'rgba(54, 162, 235, 0.2)', 
      'rgba(255, 206, 86, 0.2)', 
      'rgba(75, 192, 192, 0.2)', 
      'rgba(153, 102, 255, 0.2)', 
      'rgba(255, 159, 64, 0.2)', 
      'rgba(255, 99, 132, 0.2)' 
    ], 
    borderColor: [ 
      'rgba(255,99,132,1)', 
      'rgba(54, 162, 235, 1)', 
      'rgba(255, 206, 86, 1)', 
      'rgba(75, 192, 192, 1)', 
      'rgba(153, 102, 255, 1)', 
      'rgba(255, 159, 64, 1)', 
      'rgba(255,99,132,1)' 
      ], 
      borderWidth: 1 
    }] 
      }, 
      options: { 
        scales: { 
          yAxes: [{ 
            ticks: { 
              beginAtZero:true 
            } 
          }] 
       } 
     } 
   } 
{% endchartjs %}