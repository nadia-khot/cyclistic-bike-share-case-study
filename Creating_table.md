## Creating Table

```sql
CREATE TABLE `my_project.bike_sharing_trip_data.tripdata_comb`
AS
(SELECT
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202205_1`

UNION ALL 
SELECT ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202205_2`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202206_1`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202206_2`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202207_1`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202207_2`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202208_1`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202208_2`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202209_1`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202209_2`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202210_1`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202210_2`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202211`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202212`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202301`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202302`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202303`

UNION ALL 
SELECT 
ride_id, 
rideable_type, 
started_at, 
ended_at, 
start_station_name, 
start_station_id, 
end_station_name, 
end_station_id, 
member_casual
FROM `my_project.bike_sharing_trip_data.trip_data_202304`)
```