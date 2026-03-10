# Database Design

## Organizations

Stores tenant information.

Fields:

id
name
subdomain
subscription_plan
storage_quota
created_at

---

## Users

Stores all platform users.

Fields:

id
organization_id
name
email
password
role
status

Roles include:

system_admin
org_admin
instructor
student

---

## Courses

Fields:

id
organization_id
instructor_id
title
description
visibility

---

## Modules

Fields:

id
course_id
title
order_index

---

## Lessons

Fields:

id
module_id
title
content_type
video_url
file_url
duration

Content types:

video
pdf
audio
presentation
html
quiz
