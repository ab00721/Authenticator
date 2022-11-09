def is_valid(string, valid_characters):
    for i in string:
        if i not in valid_characters:
            return False
    return True

sample_valid_string = "1234-5678-9011-1111"
sample_invalid_string = "1234!5678.9011?1111"
valid_characters = "0123456789-"

print("Valid:", is_valid(sample_valid_string, valid_characters))
print("Valid:", is_valid(sample_invalid_string, valid_characters))