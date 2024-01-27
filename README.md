# python_str_translate
import string
test_str='dfg, is best: for! Geeks ;'
test_str=test_str.translate(str.maketrans('dfg','abc',string.punctuation))
print(test_str)
