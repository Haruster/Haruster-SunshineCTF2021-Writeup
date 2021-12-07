# Haruster-SunshineCTF2021-Writeup
- SunshineCTF2021 Writeup

## Liveness Check

- Misc문제인 Liveness Check입니다. 
- 이 문제는 그냥 문제를 열면 플래그가 보이는 것을 확인할 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/91edec6e-8c12-44a4-b619-1b43d0573a4c/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.18.03.png)

- 해당 플래그를 복사합니다.

![](https://images.velog.io/images/dsph9245/post/f9ee5774-3398-4d0e-9c17-95eae0b99b5d/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.18.11.png)

- 그리고나서 복사한 플래그를 넣어주면 

![](https://images.velog.io/images/dsph9245/post/e244452c-a624-4363-8916-29e7b4a68143/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.18.18.png)

- solve가 되는 것을 확인할 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/1a7c587d-c369-42cd-a6a5-f22c26741ae6/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.18.21.png)

## Mr Robot

- crypto문제인 Mr Robot입니다. 문제를 보면 중간에 c3Vue처럼 이상한 문자열이 있는 것을 확인할 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/9cf996aa-4d15-4b14-9afd-1acc3e7fe6d4/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.14.39.png)

- 이상한 문자열들만 뭉쳐서 base64 decoder로 돌려보면?

![](https://images.velog.io/images/dsph9245/post/a93dafd3-22af-4a03-a038-2582c0cdaeb7/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.15.35.png)

- 플래그가 나오는 것을 확인할 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/6592079f-1084-49e0-9a69-19e4efa968f1/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.15.40.png)

- 그리고나서 해당 플래그를 문제 서버에 넣어주면?

![](https://images.velog.io/images/dsph9245/post/0805ef21-645c-4f04-b55b-9e1483b7f373/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.16.48.png)

- solve가 되는 것을 확인할 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/1b9afb0a-24bf-4ace-92ff-239bf2ad96fe/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-21%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%205.17.01.png)


