## start path
* greet
  - utter_name
* inform_person{"person":"Vlad Maraev"}
  - utter_greet
  - utter_howareyou

## how are you - y/random
* random
  - utter_canichoose
* affirm
  - utter_recplaylist_yungluv

## how are you - n/random
* random
  - utter_canichoose
* deny
  - utter_howareyou

## how are you - good
* howareyougood
  - utter_relaxordance

## good - relax - y/nostalgic - nostalgia
* relax
  - utter_nostalgic
* affirm
  - utter_recplaylist_nostalgia

## good - relax - n/nostalgic - y/tired - morning mist
* relax
  - utter_nostalgic
* deny
  - utter_tired
* affirm
  - utter_recplaylist_morningmist

## good - relax - n/nostalgic - n/tired - sundays
* relax
  - utter_nostalgic
* deny
  - utter_tired
* deny
  - utter_recplaylist_sundays

## good - dance - get together - summer2019
* dance
  - utter_cluborgettogether
* gettogether
  - utter_recplaylist_summer2019
  
## good - dance - club - peach
* dance
  - utter_cluborgettogether
* club
  - utter_recplaylist_peach

## how are you - bad
* howareyoubad
  - utter_sadormad
  
## bad - sad - y/miss - mizzou
* sad
  - utter_miss
* affirm
  - utter_recplaylist_mizzou
  
## bad - sad - n/miss - sadgirl
* sad
  - utter_miss
* deny
  - utter_recplaylist_sadgirl

## bad - mad - lie - sulking
* mad
  - utter_sulkorscream
* sulk
  - utter_recplaylist_sulking
  
## bad - mad - scream - bye
* mad
  - utter_sulkorscream
* scream
  - utter_recplaylist_bye
  
