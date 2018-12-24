# 選択ソート

## 準備
- NUMBERからランダムに６個選びます
- ARRAY-INDEXの０から５の下に、ランダムに置きます

## 手順
- VARIABLE-iをDIAL-Pの１に置きます
- i が６より小さい限り、以下を繰り返します
    - テーブルの別の場所に、VARIABLE-tmpを置き、iのNUMBERをその下に置きます
    - DIAL-QにVARIABLE-jを置き、iと同じ値にします
    - DIAL-RにVARIABLE-jを置き、i+1 の値にします
    - j が 0より大きいか等しく、なおかつ j のNUMBERが tmp のNUMBERより大きい限り、以下を繰り返します
        - j のNUMBERを j+1 に動かします
        - j を１減らします
    - tmp のNUMBERを J+1 に動かします
    - i を１減らします 