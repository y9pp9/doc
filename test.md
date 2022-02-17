# 공개문서

# prod-aws-stonehawk

- #### System Details
    
    
    - **Environment:** AWS
    - **IP:** 192.168.1.1
    - **Instance Size:** T2-Micro
    - **Attached Disk Size:** 10GB
    - **RAM:** 0.5GB + 4GB Swap
    - **CPU:** 1vcpu

<p class="callout warning">DO NOT RESTART THIS MACHINE!!! Barry didn't assign a proper IP so AWS will re-allocate upon restart. This is production critical!</p>

```YAML
# 'Sammy Sosa' 노드가 반복되는 경우 - SS로 라벨을 붙여서 선언

hr:
  - Mark McGwire
  # Following node labeled SS
  - &SS Sammy Sosa
rbi:
  - *SS # Subsequent occurrence
  - Ken Griffey
```
