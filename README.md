import pandas as pd

data = {
	"One": {
		"0": 60,
		"1": 60,
		"2": 60,
		"3": 45,
		"4": 45,
		"5": 60
	},
	"Two": {
		"0": 110,
		"1": 117,
		"2": 103,
		"3": 109,
		"4": 117,
		"5": 102
	}
}

df = pd.DataFrame(data)

print(df)
