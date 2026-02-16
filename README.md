def merge_lists(list1, list2):
    return list1 + list2

if __name__ == "__main__":
    a = [1, 3, 5]
    b = [2, 4, 6]
    merged = merge_lists(a, b)
    print(f"List 1: {a}")
    print(f"List 2: {b}")
    print(f"Merged list: {merged}")
