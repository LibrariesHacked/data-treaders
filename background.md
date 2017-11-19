Background
==========

Before promoting the event we used a Google form to ask potential attendees questions, such as their data experience, which Library Carpentry modules they'd be interested in, and what they'd like to talk about at a data event.

#### How would you describe your experience of working with data?

We asked this so we could get an idea of how people viewed their experience with data. That could influence the training sessions we ran, but was mainly to get an idea of the mix of attendees. Any training would ensure every level of expertise was welcome.

| Option | Description |
| ------ | ----------- |
| Beginner | Maybe you don't work with data much, but would like to learn more |
| Intermediate | You use data, but would like to share experiences and see where you could improve |
| Expert | You do a lot with data and feel confident using it, but there's always more to learn |

{% chartjs %}
{
    type: 'pie',
    data: {
        labels: ["Beginner", "Intermediate", "Expert"],
        datasets: [{
            label: '',
            data: [18, 12, 6],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)'
            ],
            borderColor: [
                'rgba(255,99,132,1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)'
            ]
        }]
    },
    options: {

    }
}
{% endchartjs %}

#### Which Library Carpentry modules would you most like to cover?

We wanted to make this a chance to learn data skills. Library Carpentry materials are lessons in different areas around data, automation and programming. We asked people to vote on which modules they would like to learn (they could choose as many as they liked).

| Option | Number of votes | More Info |
| ------ | --------------- | --------- |
| Introduction to Data | 18 | [Library Carpentry Link](https://data-lessons.github.io/library-data-intro) |
| Tidy data and spreadsheets | 25 | [Library Carpentry Link](https://jezcope.github.io/library-spreadsheets) |
| Introduction to Programming with Python | 20 | [Library Carpentry Link](https://data-lessons.github.io/library-python-intro/) |
| Cleaning and enhancing data in OpenRefine | 23 | [Library Carpentry Link](https://data-lessons.github.io/library-openrefine/) |
| Introduction to Git | 17 | [Library Carpentry Link](https://data-lessons.github.io/library-git/) |
| Unix shell command line interface | 13 | [Library Carpentry Link](https://data-lessons.github.io/library-shell/) |
| Structured Query Language (SQL) | 18 | [Library Carpentry Link](https://data-lessons.github.io/library-sql/) |

{% chartjs %}
{
    type: 'bar',
    data: {
        labels: ["Data Intro", "Data/spreadsheets", "Python", "OpenRefine", "Git", "Command Line", "SQL"],
        datasets: [{
            label: '# of Votes',
            data: [18, 25, 20, 23, 17, 13, 18],
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

#### What else would you like to cover?

We were interested in what people would want to talk about. Everyone will be free to pitch on the day, but these are a selection of suggestions we've already received.

| Answers |
| ------- |
| Open data advocacy
| How to talk to leaders and managers about open data |
| How to allay fears and influence senior managers |
| How to work with Local authority IT teams or departments |
| How to extract data from specific LMSs |
| Using/identifying tools for working with data, from data creation, data cleansing/normalization to manipulating data |
| Open data and libraries |
| What primary data libraries own and what they use it for.
| Using R Studio (R) |
