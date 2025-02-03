## dash-board 
    profile_overview{
        profile_pic(upload, file.size: 25MB)
        full_name()
        email(max: 45)
        relationship_to_student()
        phone_number 
    }
    settings{
        chnage_password{
            new_password(min: 8, max: 30)
            confirm_password(min: 8, max: 30)
        }
    }

events{
    event_list{
        search()
    }
    calendar()
}


## class 
    assignment_submisssion{
        attachment(upload, max.file-size: 25MB)
        your_responce(max: 250)
    }
    assignment_submission{
        attachment(upload, max.file-size: 25MB)
        comment()
    }

## E-library 
    content{
        search()
    }

### events 
    events_list()
    calender()

## notice-board
    search()
    banner_image()
    banner_image()
    banner_image()
    banner_image()
    
## messaging 
    search()

## school-calender()
    search()