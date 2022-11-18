//для создания таблицы

CREATE TABLE `kata231`.`users`
(
    `ID`      INT         NOT NULL AUTO_INCREMENT,
    `name`    VARCHAR(45) NULL,
    `surname` VARCHAR(45) NULL,
    `age`     TINYINT     NULL,
    `email`   VARCHAR(45) NULL,
    PRIMARY KEY (`ID`)
);
insert into users (id, name, surname, age, email)
values(1, 'Иван', 'Иванов', 67, 'ivan@gmail.com');
insert into users (id, name, surname, age, email)
values(2, 'Иван2', 'Иванов2', 85, 'ivan2@gmail.com');
insert into users (id, name, surname, age, email)
values(3, 'Иван3', 'Иванов3', 44, 'ivan3@gmail.com');