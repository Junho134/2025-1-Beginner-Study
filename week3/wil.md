commit 되돌리는 방법 amend, reset, revert
ammend: 완전히 새로운 commit으로 대체, vim으로 commit 메세지 수정
reset: 다 같이 작업하는 곳에서는 사용x
       --soft: commit만 취소, staging area로 돌아감
      --mixed: working directory로 돌아감
       --hard: 변경 사항 모두 제거, 이전 커밋으로 돌아감
revert: commit을 제거하지 않고 되돌림
        revert --no-edit 편집기 진입 없이 바로 revert가능