-- phpMyAdmin SQL Dump
-- version 5.1.1
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Aug 13, 2021 at 02:00 PM
-- Server version: 10.4.20-MariaDB
-- PHP Version: 7.4.22

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `03_amiroh fatma`
--

-- --------------------------------------------------------

--
-- Table structure for table `db_03_amiroh fatma`
--

CREATE TABLE `db_03_amiroh fatma` (
  `NIM` varchar(20) NOT NULL,
  `NAMA_SISWA` varchar(30) NOT NULL,
  `JURUSAN` varchar(25) NOT NULL,
  `ANGKATAN` varchar(10) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `db_03_amiroh fatma`
--

INSERT INTO `db_03_amiroh fatma` (`NIM`, `NAMA_SISWA`, `JURUSAN`, `ANGKATAN`) VALUES
('13454555', 'db_03_Amiroh Fatma', 'REKAYASA PERANGKAT LUNAK', '2020');
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
