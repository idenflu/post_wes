# 보관
보관 (Storage) 설비는 화물을 보관

## Property

### StorageType: Enum
스토리지 타입 (ASRS 등)

### Cell: Object
보관 위치에 대한 정보

- name (이름)
- line (호기)
- level (단)
- row (행, X축)
- column (열, Y축)
- deep
- Status (셀의 상태)
  - 사용여부
  - 재고존재여부
- grade (셀의 등급?)
- isReserved (입고, 출고, 리로케이션 등의 행위로 현재 예약이 되어있는지?)
- ItemId
  - 해당 셀의 아이템 대표 아이디?
- RelationEquipmentId
  - 해당 셀의 영향을 주는 크레인등의 아이디? (적재로직에서 해당 셀에 엮인 크레인등의 상태를 확인할 필요가있음)

### ConnectionStatus: Object
- 연결 상태
- 최근 연결 성공 일시