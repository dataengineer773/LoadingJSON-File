We need to load a JSON file for data preprocessing, The solution is The pandas library provides read_json to convert a JSON file into a pandas object, Importing JSON files into pandas is similar to the last few recipes we have seen. The key difference is
the orient parameter, which indicates to pandas how the JSON file is structured. However, it might take some experimenting to figure out which argument (split, records, index, columns, and values)
is the right one. Another helpful tool pandas offers is json_normalize, which can help convert semistructured JSON data into a pandas DataFrame.
