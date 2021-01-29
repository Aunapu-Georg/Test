class Faculty:

    def __init__(self, faculty, list_of_classes):

        print('Введите название факультета (типа данных str): ')
        self.faculty = faculty
        print('Введите расписание занятий (типа данных list): ', end='\n\n')
        self.list_of_classes = list_of_classes

    def info(self):

        print('Факультет: ', self.faculty)
        print('Расписание уроков: ')
        for i in range(len(self.list_of_classes)):

            print('   ', i + 1, '.', ' ', self.list_of_classes[i], sep='', end='\n\n')


class Class:

    def __init__(self, subject, type, tutor, group, day, time, auditorium):

        print('Введите название предмета (представителя данного Subject): ', end='')
        self.subject = subject
        print('\n', 'Введите тип занятия (тип данных str): ', end='')
        self.type = type
        print('\n', 'Введите учителя, проводящего данное занятие (представителя класса Tutor): ', end='')
        self.tutor = tutor
        print('\n', 'Введите учебную группу (представителя класса Group): ', end='')
        self.group = group
        print('\n', 'Введите день проведения данного занятия (тип данных str): ', end='')
        self.day = day
        print('\n', 'Введите время начала данного занятия в формате hh:mm (тип данных str): ', end='')
        self.time = time
        print('\n', 'Введите аудиторию, в которой будет проводиться данное занятие (представитель класса Auditorium): ', end='')
        self.auditorium = auditorium
        print('\n\n')

    def info(self):

        print('Предмет:', self.subject)
        print('Тип занятия:', self.type)
        print('Преподаватель:', self.tutor)
        print('Учебная группа:', self.group)
        print('День:', self.day)
        print('Время:', self.time)
        print('Аудитория: №', self.auditorium)


faculty = Faculty('экономический', ['микроэкономика', 'макроэкономика', 'мировая экономика', 'экономика России'])
faculty.info()
