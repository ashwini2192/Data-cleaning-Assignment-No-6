# Data-cleaning-Assignment-No-6
It happens all the time: someone gives you data containing malformed strings,
Python, lists and missing data. How do you tidy it up so you can get on with the
analysis?
Take this monstrosity as the DataFrame to use in the following puzzles:
        df = pd.DataFrame({'From_To': ['LoNDon_paris', 'MAdrid_miLAN',
        'londON_StockhOlm',
        'Budapest_PaRis', 'Brussels_londOn'],
        'FlightNumber': [10045, np.nan, 10065, np.nan, 10085],
        'RecentDelays': [[23, 47], [], [24, 43, 87], [13], [67, 32]],
        'Airline': ['KLM(!)', '<Air France> (12)', '(British Airways. )',
        '12. Air France', '"Swiss Air"']})
