# matsushita25_cog_dataset
This repository contains the open-source dataset published in the short paper at IEEE CoG 2025.

## Creating a dataset
The video set for this experiment was created based on 32 one-on-one videos collected from [SMASH corpus](https://ss-takashi.sakura.ne.jp/corpus/smash/).
SMASH corpus includes match videos (without audio), commentary audio, and CSV files annotated with speech start and end times as well as topic tags.

## 'result.csv':Participant attributes and video stimuli information
| gender | age | known | experience | third_person_commentary | first_person_commentary | place | inst_exp  | inst_type | inst_year |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LyveIdDrBe | male     | 40s | jpn         | pop       | neutral   | 15-18     | home | no | none | none | 
| ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... |

gender,age,known,experience,third_person_commentary,first_person_commentary,place,user_id,score,filename,original_file,delay,utterance_id,topic_tag,lancersResultId
男性,30代,知っている,機会があれば，家族や友人とプレイをすることもある程度,数回程度見たことがある,数回程度見たことがある,自宅,user42399_20241205201949-0272,3,MM3output_id14_delay-1.0.mp4,MM3,-1,14,対戦風景,LRI045579972

## License
- MIT

## Contributors
- Ryosuke Matsushita (Keio University, Japan, main contributor)
- Shinnosuke Takamichi (Keio University, Japan)

## Reference
- Ryosuke Matsushita, Ryosuke Sakai, Koki Fukuda, Shinnosuke Takamichi, Kota Iura, Yuki Saito, Graham Neubig, Katsuhito Sudoh, Hiroya Takamura, Tatsuya Ishigaki, "Measuring Time Delay Tolerance in Third-Person Live Commentary for Super Smash Bros. Ultimate", IEEE CoG, 2025.
