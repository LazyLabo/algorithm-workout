# 選択ソート

## 準備
- NUMBERからランダムに６個選びます
- ARRAY-INDEXの０から５の下に、ランダムに置きます

## 手順
- VARIABLE-iをDIAL-Pの５に置きます
- 別の紙に、VARIABLE-lenを使ってconstを作り、6を値として書きます
- i が len-1 より小さい限り、以下を繰り返します
    - DIAL-QにVARIABLE-minを置き、iと同じ値にします
    - DIAL-RにVARIABLE-jを置き、i+1の値にします
    - j が len より小さい限り、以下を繰り返します
        - もし j のNUMBERが min のNUMBERより小さいなら、
            - min を j と同じ値いします
        - j を１増やします
    - i のNUMBERを、min のNUMBERと交換します
    - i を１増やします 