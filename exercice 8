function houseEnergyScore(housingList):
get_grade = lambda consumption: (
        'G' if consumption >= 450 else
        'F' if consumption >= 330 else
        'E' if consumption >= 230 else
        'D' if consumption >= 150 else
        'C' if consumption >= 90 else
        'B' if consumption >= 51 else
        'A'
    )
 
 
 
   
housingList = [
    ['Log', 20], 
    ['Villa', 212], 
    ['Flat', 232], 
    ['Loft', 345], 
    ['Castle', 560], 
    ['Igloo', 12],
    ['Hutch', 30]
]

print(houseEnergyScore(housingList))


// This lines will display the result for you
if (typeof houseEnergyScore === "function") {
	const scores = [["Hutch", 30],["Loft", 345], ["Castle", 560], ["Igloo", 12], ["Villa", 232], ["Flat", 212]];
	const result = houseEnergyScore();
	displayResult(result);
}
