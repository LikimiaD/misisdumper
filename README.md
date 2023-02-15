# ID для работы с API LK MISIS
### По мере надобности мы будем заполнять его.

### Пример JSON для кабинета с id 1085
```
'schedule_header' => День недели
'beel N', где N>0 => Расписание пар в определенную пару на всю неделю

{
  'status': 'FOUND',
  'start_date': '??????',
  'start_date_show': '??????',
  'end_date': '??????',
  'end_date_show': '??????',
  'prev_date': '??????',
  'next_date': '??????',
  'teacher_id': None,
  'group_id': None,
  'room_id': '1085',
  'schedule_header': {
    'header': {
      'type': 'static',
      'text': 'Время'
    },
    'day_1': {
      'type': 'listable',
      'text': 'понедельник ',
      'short_text': 'Пн',
      'date': '13.02.23'
    },
    'day_2': {
      'type': 'listable',
      'text': 'вторник ',
      'short_text': 'Вт',
      'date': '14.02.23'
    },
    'day_3': {
      'type': 'listable',
      'text': 'среда ',
      'short_text': 'Ср',
      'date': '15.02.23'
    },
    'day_4': {
      'type': 'listable',
      'text': 'четверг ',
      'short_text': 'Чт',
      'date': '16.02.23'
    },
    'day_5': {
      'type': 'listable',
      'text': 'пятница ',
      'short_text': 'Пт',
      'date': '17.02.23'
    },
    'day_6': {
      'type': 'listable',
      'text': 'суббота ',
      'short_text': 'Сб',
      'date': '18.02.23'
    }
  },
  'schedule': {
    'bell_1': {
      'header': {
        'type': 'bell',
        'start_lesson': '09:00',
        'end_lesson': '10:35'
      },
      'day_1': {
        'type': 'lesson',
        'lessons': [
          
        ]
      },
      'day_2': {
        'type': 'lesson',
        'lessons': [
          
        ]
      },
      'day_3': {
        'type': 'lesson',
        'lessons': [
          
        ]
      },
      'day_4': {
        'type': 'lesson',
        'lessons': [
          
        ]
      },
      'day_5': {
        'type': 'lesson',
        'lessons': [
          {
            'subject_id': 304,
            'subject_name': 'Информатика',
            'teachers': [
              {
                'id': 188563,
                'post': 'Почасовик',
                'name': '??????'
              }
            ],
            'groups': [
              {
                'id': 7910,
                'name': '??????',
                'subgroup_id': 11,
                'subgroup_name': '1'
              }
            ],
            'rooms': [
              {
                'id': 1085,
                'name': 'Б-823-УВЦ'
              }
            ],
            'room_id': 1085,
            'room_name': 'Б-823-УВЦ',
            'type': 'Лабораторные',
            'in_ceiling': True,
            'other': None,
            'other1': None
          }
        ]
      },
      'day_6': {
        'type': 'lesson',
        'lessons': [
          
        ]
      }
    },
    ......
```
###### По всем вопросам пишите в Telegram @likimiad