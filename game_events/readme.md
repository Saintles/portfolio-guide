**Create database**
````sql
create table game_events (
user_id char(10) not NULL,
event_name varchar(45) NOT NULL,
level_name varchar(45),
level_success tinyint,
event_date DATE,
revenue decimal(8, 5)
);
