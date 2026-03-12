In case of graph issues try:
change on line 134
#scales: {
            x: { 
                type: 'linear',  
                position: 'bottom',
                title: { display: true, text: '1000 / T (K⁻¹)' } 
            },
            y: { 
                title: { display: true, text: 'ln(ρ)' } 
            }
        }

change on line 122
scatter-->line
additional lines on data set
#borderColor: "#00d2ff",
                    tension: 0.2,
