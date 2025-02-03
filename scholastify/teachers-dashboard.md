## profile-overview
    full_name(min:10, max:40)
    email(max: 45)
    last_login
    position_role
    phone_number(max: 30)

## password
    new_password(min: 20, max: 40)
    confirm_password(min: 20, max: 40)

## HR 
    daily_attendance{
        check-btn{
        present:
        absent:
        on leave:
        }
    }
    my_attendance{
        search()
    }
    salary(
        search()
    )
    salary_slips{
        search()
    }
    payment_history{
        search()
    }
    deduction_and_bonuses{
        search()
    }
    leave_application{
        leave_type(drop_down)
        start/end_date(date)
        reason(max: 250)
    }
    leave_status{
        search()
    }
    leave_balance{
        search()
    }
    leave_history{
        search()
    }
    submit_a_query{
        query_type(drop_down)
        attachment(upload, max-file-size: 25MB)
        discription(max: 250)
    }
    query_status{
        serach()
    }

## student 
    all_student{
        search()
    }
    real_management{
        search()
    }
    edit_result{
        subject(drop_down)
        assignment()
        remark()
        continuous_assessments()
        exam()
        grade()
    }
    student_assessment{
        class(drop_down)
        subject(drop_down)
        assignment()
        remark()
        student_name()
        continuous_assessments()
        exam()
        grade()
    }

## attendance 
    daily_attendance{
        search()
    }
    add_note(max: 100)
    attendance_record{
        search()
    }
    
## class
    syllabus{
        search()
    }
    add_syllabus_by_chapter{
        subject(drop_down)
        topics_covered()
        start_date(date)
        chapter()
        resource()
        end date()
    }
    add_syllabus_by_upload{
        attachment()
    } 
    my_subject{
        search()
    }
    mathematics{
        search()
    }
    lesson_plan{
        search()
    } 
    add_single_lesson_plan{
        subject(drop_down)
        objective()
        activities()
        class_date(date)
        material_needed()
        attachment(upload, max.file-size: 25MB)
    }
    class_activities{
        search()
    }
    add_activity{
        subject(drop_down)
        activity_name()
        start_date(date)
        mark_obtainable()
        activity_type(drop)
        description()
        end_date(date)
        mark_obtainable()
        question()
        attachment(upload, max.file-size: 25MB)
    }
    assignment{
        attachment(upload, max.file-size: 25MB)
        add_a_comment(max: 250)
    }
    group_work{
        attachment(upload, max.file-size: 25MB)
        add_a_comment(max: 250)
    }
    assignment_grading{
        grade()
    }
    class_events{
        search()
    }
    add_event{
        event_details(drop_down)
        event_date(date)
        location()
        organizer()
        class(drop_down)
        time()
        description(max: 250)
    }

## E-library
    add_a_new_folder{
        folder_title{
            talent_input()
            description()
        }
    }
    grade{
        search()
    }
    upload_file{
        video_title()
        file_type(drop_down)
        assign_to_subject(drop_down)
        description(max: 250)
        attachment(upload, max.file-size: 25MB)
        assign_class(drop_down)
    }

## events
    event{
        search()
        calendar{
            search()
        }
    }

## messsaging
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
    