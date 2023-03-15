docker compose --profile download up --build
# wait until its done, then:
docker compose --profile [ui] up --build
# where [ui] is one of: invoke | auto | auto-cpu | sygil | sygil-sl


docker compose up -d --build
