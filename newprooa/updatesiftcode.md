# seeder 

# Update Shift 

```php
$shiftSchedule = new  ShiftSchedule();
           $shiftSchedule->sc_user_id =1 ;
           $shiftSchedule->as_shift_id = 2;
           $shiftSchedule->shift_date = '2024-09-16';
           $shiftSchedule->day_of_type = 0;
           $shiftSchedule->save();
   
           $shiftSchedule = new  ShiftSchedule();
           $shiftSchedule->sc_user_id =1 ;
           $shiftSchedule->as_shift_id = 2;
           $shiftSchedule->shift_date = '2024-09-17';
           $shiftSchedule->day_of_type = 0;
           $shiftSchedule->save();
   
           $shiftSchedule = new  ShiftSchedule();
           $shiftSchedule->sc_user_id =1 ;
           $shiftSchedule->as_shift_id = 2;
           $shiftSchedule->shift_date = '2024-09-18';
           $shiftSchedule->day_of_type = 0;
           $shiftSchedule->save();
   
           $shiftSchedule = new  ShiftSchedule();
           $shiftSchedule->sc_user_id =1 ;
           $shiftSchedule->as_shift_id = 3;
           $shiftSchedule->shift_date = '2024-09-19';
           $shiftSchedule->day_of_type = 0;
           $shiftSchedule->save();
```