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
    leave_permission_request{
        request-search()
    }
    staff_attendance{
        attendance-search()
    }

    admission{
        admission-search()
    }

    Danjuma_Danlima{
        student_info
            admission_number()
            class()
            middle_name(min: 3, max: 10)
            date_of_birth(date)
            address(max: 40)
            email(max: 45)
            mobile_number(max: 30)
            admisssion_date(date)
            first_name(min: 3, max: 20)
            last_name(min: 3, max: 20)
            gender(drop_down)
            state(drop_down)
            LGA(drop_down)
            previous_shool()
    }

## teachers 
    teachers{
        search()
    }
    basic_detail{
        teachers_name(min: 3 max: 15)
        date_of_birth(date)
        mobile_number(max: 30)
        years_of_experience()
        gender(drop_down)
        date_of_employment(date)
        qualification()
    }
    residential{
        state(drop_down)
        lga(drop_down)
        address(max: 30)
    }
    login_details{
        user_name()
        email(max: 45)
        password(min: 20, max: 40)
        repeat_password(min: 20, max: 40)
    }
    assign_class{
        class()
    }
    assign_subject{
        subject()
    }

## parents
    parents{
        seach()
    }
    add_new_parents{
        basic_detail{
            title()
            middile_name(min: 3, max: 10)
            date_of_birth(date)
            mobile_number(max: 20)
            education_qualification()
            annual_income()
            first_name(min: 3, max: 20)
            last_name(min: 3, max: 20)
            gender()
            email(max: 45)
            occupation()
        }
        residential address{
            state(drop_down)
            lga(drop_down)
            address()
        }
        login{
            username()
            email(max: 45)
            password(min: 20, max: 40)
            repeat_password(min: 20, max: 40)
        }
       
    }

## students

student{
    select(drop_down)
    }
    input_student_id_number{
            id_number()
    }

## messaging
    search()

## events 
    event_list{
        search()
    }
    basic_details{
        event_list(drop_down)
        time(time)
        description(min: 30, max: 100)
        date_of_birth(date)
        location(max: 30)
        organizer()
    }
    calender()

## finance
    payment_history{
        search()
    }
    staff_salaries{
        search()
        search_attendance()
        pay_salary{
            staff_name(drop_down)
            Gross_salary()
            net_salary()
            payment_date(date)
            deduction(drop_down)
        }
    }
    generate_invoice{
        parent_name(min: 3, max: 20)
        student_id
        session(drop_down)
        amount_to_pay()
        student_name()
        payment_for(drop_down)
        term(drop_down)
    }
    invoice()
    
## notice-board
    search()
    add_to_notice_board{
        media(file)
        title()
        tags(drop_down)
        notice_by()
        more_about_notice(max: 250)
    }

## school-calender
   create_event{
        title()
        date(get_date)
        time(real_time)
        notice_by()
        message(max: 250)
   }
   edit_event{
        title()
        date(get_date)
        time(real_time)
        notice_by()
        message(max: 250)
   }

## subject
    search()
    add_subject{
        subject_id()
        description(max: 250)
        subject_name()
        offered_by_class(drop_down)
    }

## admin-user
    search()
    add_admin_user{
        user_name()
        full_nmae(max: 20)
        email(max: 45)
        role(drop_down)
        activity(drop_down)
    }
    profile_overview{
        full_name(max: 20)
        email(max: 45)
        last_login()
        position()
        phone_number()
    }

    
    


        