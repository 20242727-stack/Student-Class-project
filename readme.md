class Student:
    def __init__(self, student_id, name, age):
        self.student_id = student_id
        self.name = name
        self.age = age
        self.courses = []

    def add_course(self, course):
        self.courses.append(course)

    def display_info(self):
        print("ID:", self.student_id)
        print("Name:", self.name)
        print("Age:", self.age)
        print("Courses:", self.courses)


student1 = Student(102, "Sabrina", 23)
student1.add_course("Python")
student1.add_course("Database")
student1.display_info()
