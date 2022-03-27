boys = ['Peter', 'Alex', 'John', 'Arthur', 'Richard']
girls = ['Kate', 'Liza', 'Kira', 'Emma', 'Trisha']

if len(boys) != len(girls):
  print('Кто-то может остаться без пары!')
else:
  couples = zip(sorted(boys), sorted(girls))
  print('Идеальные пары:')
  for x in couples:
    print(x[0], ' и ', x[1])