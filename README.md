# Pyhton-email-slicer

def email_slicer(email):
  # Split the email address into a list at the @ symbol
  email_parts = email.split("@")
  
  # Return the first part (the username) and the second part (the domain)
  return email_parts[0], email_parts[1]

# Test the function
print(email_slicer("john@example.com"))  # Output: ("john", "example.com")
