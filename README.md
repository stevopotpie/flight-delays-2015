
# Airline Delays and Cancellations (2015)

## Project Summary
This project explores U.S. domestic airline delays and cancellations in 2015 using real-world flight data. The goal was to uncover operational patterns, pinpoint bottlenecks, and explore seasonal or airport-specific issues that impact air travel.

## Key Insights

### Cancellations:
- **Top Reasons:** Carrier delays, weather, NAS (airspace), security, and late-arriving aircraft.
- **Seasonality:** Cancellations peaked in winter months—especially February—suggesting weather and scheduling constraints play a large role.
- **LGA Alert:** LaGuardia (LGA) stood out with a significantly higher cancellation rate (~4.5%) compared to JFK (~2%) and EWR (~3%). Among the 15 most canceled routes, the majority involved LGA either as origin or destination.

### Delay Patterns:
- **By Cause:** Carrier delays were the largest contributor to total delay time, followed by late aircraft and NAS (National Aviation System).
- **By Time:** Delays built steadily through the day, peaking in late afternoon and early evening (4–8 PM).
- **Worst Airports by Avg Departure Delay:** Aspen (ASE), Eagle-Vail (EGE), Chicago O’Hare (ORD), and Trenton (TTN) had the worst averages.
- **Best Airports:** Many small regional airports had low delays, but due to low traffic, insights may be limited. A more fair comparison focused on major hubs.

### Major Hub Comparison:
- **Best Performing Hubs:** Seattle (SEA), Minneapolis (MSP), Charlotte (CLT)
- **Worst Performing Hubs:** Chicago O’Hare (ORD), Newark (EWR), Miami (MIA)

## Files Included
- `Airline_Delay_Analysis.ipynb`: Jupyter Notebook with full analysis
- `/data/`: Cleaned CSV file for analysis
- `/visuals/`: PNG images used in the notebook and for documentation
- `README.md`: This documentation

## Tools Used
- Python (pandas, matplotlib)
- Jupyter Notebook
- GitHub (version control and documentation)
- Power BI (planned for dashboard buildout)

## Future Extensions
- Add Power BI dashboard
- Compare across multiple years
- Explore aircraft types and delay correlation
- Study route density and performance
