# Lab2 Repository

    import sys

    def print_args():
    # Print the script name
    print("Script name:", sys.argv[0])

    # Check if arguments were provided
    if len(sys.argv) > 1:
        # Print the script name along with provided arguments
        print("Script name and variables:", ' '.join(sys.argv))

     # Call the function
print_args()
