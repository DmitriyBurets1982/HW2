-- Build
docker build -t hw2 .

-- Run
docker run -dp 8000:8080 hw2

-- Run compose
docker-compose up hw2 -d

-- Exec
localhost:8000/health