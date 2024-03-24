class ListManipulator:
    def _init_(self):
        self.internal_list = []

    def add_elements(self, elements):
        self.internal_list.extend(elements)

    def remove_duplicates(self):
        self.internal_list = list(set(self.internal_list))

    def reverse_list(self):
        self.internal_list.reverse()

    def sort_list(self):
        self.internal_list.sort()

    def get_unique_elements(self):
        return list(set(self.internal_list))

    def remove_element(self, element):
        if element in self.internal_list:
            self.internal_list.remove(element)

    def get_list(self):
        return self.internal_list- class ListManipulator:
    def _init_(self):
        self.internal_list = []

    def add_elements(self, elements):
        self.internal_list.extend(elements)

    def remove_duplicates(self):
        self.internal_list = list(set(self.internal_list))

    def reverse_list(self):
        self.internal_list.reverse()

    def sort_list(self):
        self.internal_list.sort()

    def get_unique_elements(self):
        return list(set(self.internal_list))

    def remove_element(self, element):
        if element in self.internal_list:
            self.internal_list.remove(element)

    def get_list(self):
        return self.internal_list
