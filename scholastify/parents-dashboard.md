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

## messages
    search()
    notice_board{
        search()
        banner_image()
        banner_image()
        banner_image()
        banner_image()
    }

## school-calender
    search()