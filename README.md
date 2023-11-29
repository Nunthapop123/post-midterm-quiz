i just added 
movies = []
with open(os.path.join(__location__, 'movies.csv')) as f:
    rows = csv.DictReader(f)
    for r in rows:
        movies.append(dict(r))
this code to make Table class can work with csv file propely 
