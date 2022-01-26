//lv.1
//문제 출처 https://programmers.co.kr/learn/courses/30/lessons/86051?language=javascript
//풀이 코드
function solution(numbers) {
    let arr = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
    let answer = 0;
    for (let i = 0; i < numbers.length; i++){
        arr[numbers[i]] = 1;
    }
    for (let k = 0; k < arr.length; k++) {
        if (arr[k] == 0){
            answer += k;
        }
    }
    return answer;
}
