Voyage of the Data Treader
==========================

Monday 20th November, Liverpool City Library.

[Sign up to Voyage of the Data Treader here](https://www.eventbrite.co.uk/e/voyage-of-the-data-treader-library-data-camp-2017-registration-37308706345) with Eventbrite.

Are you interested in open data? Want to know more about using data to improve your library service? Or just want to play with some library data?

Library Data Camp will be a mix of workshops, discussions, and data playing. Anyone interested in using data to improve library services is welcome.

### Background

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