# IARC_Controls


  controls.cpp--

 -New topic added :topic name : groundbot/tap
 +

 +
 +                topic name : groundbot/tap
                  message type - strategy/navigate_quad
                  Header header
                  int32 id
                  float64 x
                  float64 y
                  float64 z

 +                mode = 1 for tap in int32 mode
                       = 0 for bump i.e land in front for 180 degree turn
                       = -1 for just following the groundbot
 +                id = 1 for navigating to a point, 4-13 for groundbots
