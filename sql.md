CREATE DATABASE contact;

USE contact;

CREATE TABLE IF NOT EXISTS contact (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL,
    number BIGINT NULL,
    message TEXT NOT NULL
);
