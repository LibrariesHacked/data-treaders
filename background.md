Background
==========

We ran a google form to ask people some brief questions, such as their level of data experience, which Library Carpentry modules they'd be most interested in, and what they would like to talk about at a future library data event.  These were the results.

#### How would you describe your experience of working with data?

We asked this question so we could get an idea of how people saw their own experience with data. That could potentially influence the training sessions we ran, but really it was just to get an idea of the particular mix of attendees we would get. Any training sessions would be designed to ensure every level of expertise was welcome - having an idea of the mix is good for planning how to separate groups.

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

#### Which Library Carpentry modules would you most like to cover?





{% chartjs %}
{
    type: 'bar',
    data: {
        labels: ["Red", "Blue", "Yellow", "Green", "Purple", "Orange"],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255,99,132,1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
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