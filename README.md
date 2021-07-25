# Funds
Code and Data for the HarvardX Data Science Certificate final (CYO) project submission

Summary    : The project analyzes cross-sectional Exchange Traded Fund (ETF) and Mutual Fund (MF) data to draw conclusions about 
             their risk-adjusted returns and consequently predict fund performance.
             
             ETF's and MF's are vehicles allowing investors, investment advisors, and portfolio managers (PM's) to gain exposure to different
             investment strategies. 
             
             The fund's investment strategies are set within a prospectus specifying its investment universe (ie what types of securities
             or financial instruments can be dealt), other constraints, performance benchmarks (where relevant) and other information.
             
             These users are faced with a plethora of funds to select from in order to achieve their investment objectives.
             
             The purpose of this project is to feed their fund selection process. 
             
             Two essential elements typically help to determine their choice(s) among others: 
             1- The return objective: the minimum required return that must be achieved (this is an input) 
             2- The risk assumed to achieve this return must also be taken into account
                A measure of risk-adjusted return (the Sharpe Ratio) is used to ensure that an appropriate risk-reward balance is achieved.
                The Sharpe Ratio uses the standard deviation of returns as its risk proxy.
                
             We consider a 3-year investment horizon and therefore we : 
             1- Predict the fund's 3-year Mean Annual Return (MAR) 
             2- Classify funds based on their 3-year Sharpe Ratio, establishing a minimum hurdle a fund should exceed in order to be considered
                for selection. This ensures the investment risk is managed from the outset.

Data Files : 'etfs.csv'; 'mutual funds.csv'
