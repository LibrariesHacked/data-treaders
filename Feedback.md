## Feedback 

We wanted to know what people thought of Library Data Day, to find out which sessions attendees got the most out of and to see how our outcomes were met. 

All attendees were sent a link to a [Google form](https://goo.gl/forms/5JSfERpKy2omwleI2) asking for feedback. 

#### Which sessions did you attend that you personally got the most out of?

Library Data Camp was mostly run as an unconference so many sessions were decided on the day. We thought it would be useful to know which sessions attendees got the most out of personally. 

{% chartjs %} 
{ 
  type: 'bar', 
  data: { 
  labels: ["Data Intro", "Open Data 101", "Open Data advocacy", "Extracting data", "Core dataset/schema","Social media", "OpenRefine","Text adventures", "API", "Publish your first dataset", "Social value", "Open Data Camp",], datasets: [{ 
    label: '# of attendees', 
    data: [3, 8, 2, 1, 1, 2, 3, 2, 4, 4, 2, 1], 
    backgroundColor: [ 
      'rgba(255, 99, 132, 0.2)',
      'rgba(54, 162, 235, 0.2)',
      'rgba(255, 206, 86, 0.2)',
      'rgba(75, 192, 192, 0.2)',
      'rgba(153, 102, 255, 0.2)',
      'rgba(255, 159, 64, 0.2)',
      'rgba(255, 99, 132, 0.2)',
      'rgba(97, 194, 45, 0.2)',
      'rgba(224, 226, 74, 0.2)',
      'rgba(25, 205, 175, 0.2)',
      'rgba(207, 40, 229, 0.2)',
      'rgba(229, 40, 90, 0.2)'
      
    ], 
    borderColor: [ 
      'rgba(255, 99, 132, 1)',
      'rgba(54, 162, 235, 1)',
      'rgba(255, 206, 86, 1)',
      'rgba(75, 192, 192, 1)',
      'rgba(153, 102, 255, 1)',
      'rgba(255, 159, 64, 1)',
      'rgba(255, 99, 132, 1)',
      'rgba(97, 194, 45, 1)',
      'rgba(224, 226, 74, 1)',
      'rgba(25, 205, 175, 1)',
      'rgba(207, 40, 229, 1)',
      'rgba(229, 40, 90, 1)'
    
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

#### Learning outcomes 

While planning Library Data Camp, we put together some outcomes and were keen to find out how much these had been met. In the feedback we asked how much attendees had learnt from the day based on these outcomes.

##### 1. Understand key data terms 

{% chartjs %}
{
    type: 'pie',
    data: {
        labels: ["Lots", "Some", "None"],
        datasets: [{
            label: '',
            data: [6, 8, 0],
            backgroundColor: [
                'rgba(117, 14, 66, 0.2)',
                'rgba(148, 223, 242, 0.2)',
                'rgba(217, 217, 39, 0.2)'
            ],
            borderColor: [
                'rgba(117,14,66,1)',
                'rgba(148, 223, 242, 1)',
                'rgba(217, 217, 39, 1)'
            ]
        }]
    },
    options: {

    }
}
{% endchartjs %}

##### 2. Know what to do with your library data to demonstrate impact and make informed decisions

{% chartjs %}
{
    type: 'pie',
    data: {
        labels: ["Lots", "Some", "None"],
        datasets: [{
            label: '',
            data: [4, 8, 3],
            backgroundColor: [
                'rgba(117, 14, 66, 0.2)',
                'rgba(148, 223, 242, 0.2)',
                'rgba(217, 217, 39, 0.2)'
            ],
            borderColor: [
                'rgba(117,14,66,1)',
                'rgba(148, 223, 242, 1)',
                'rgba(217, 217, 39, 1)'
            ]
        }]
    },
    options: {

    }
}
{% endchartjs %}

##### 3. Learn key skills in manipulating data

{% chartjs %}
{
    type: 'pie',
    data: {
        labels: ["Lots", "Some", "None"],
        datasets: [{
            label: '',
            data: [3, 8, 3],
            backgroundColor: [
                'rgba(117, 14, 66, 0.2)',
                'rgba(148, 223, 242, 0.2)',
                'rgba(217, 217, 39, 0.2)'
            ],
            borderColor: [
                'rgba(117,14,66,1)',
                'rgba(148, 223, 242, 1)',
                'rgba(217, 217, 39, 1)'
            ]
        }]
    },
    options: {

    }
}
{% endchartjs %}

