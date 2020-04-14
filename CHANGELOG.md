# Changelog
작업하면서 변경점은 모두 이 기록에 저장합니다.
할수있으면 영어로도 추가내용을 적기

이 체인지 로그 포맷은 [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)를 기반으로 작성됨,

## [Unreleased]
### Added
- 새로운 종족 쌍두 오우거 추가. 2개의 무기와 2개의 목걸이를 낄 수 있음. 그러나 방패를 낄 수 없음
  - Added two-headed ogre(playable). Can wear 2 weapons and 2 amulets. But you can't wear a shield
  
- 독물의 추출, 증산 추가
  - Added Fulsome Distillation, Evaporate spell
  
- 독물의 추출을 위한 나쁜 포션(독, 맹독, 맹물)추가. 추출에서만 나오는 포션이며 자연 드랍되면 버그임
  - Added bad potions (poison, strong poison, water) for Evaporate. only create by Fulsome Distillation
  
- 가속 마법 복구
  - rollback Haste
  
- 둔기 특성화. 이제 둔기로 적을 죽일때마다 시체를 넉백시킬 수 있고 넉백된 시체는 적에게 데미지를 줌
  - add mace&flail ability. Now every time you kill an enemy with a mace&flail weapon, you can knock back the corpse, and the knocked back corpse deals damage to the enemy
  
- 새로운 메인 타이틀 이미지 추가 (logal-image)
  - Add new title artwork (logal-image)
  
- 힐완드 복구
  - Rollback wand of heal wounds

### Changed
- 오우거 둔기적성 +3으로 변경 (기존 -1)
  - Ogre Maces & Flails aptitude changed to +3 (prev -1)

- 드라코들은 이제 냉혈 변이를 가지지않음
  - All dracos are no longer cold blooded

- 회색을 제외한 드라코 전원 14레벨에 영구 비행 변이를 얻도록 변경
  - All dracos will gain big wing mutation at xl 14 except grey

- 메뉴 컬러링을 위한 태그(fixed_artefact, random_artefact) 추가. 픽다트의 기본 색깔을 노란색으로 변경
  - Added Menu/colouring Prefixes(fixed_artefact, random_artefact). Changed the default color of the fixed artefact to yellow
  
- 오조크브의 갑옷은 이제 움직여도 풀리지않음
  - Ozocubu's armor no longer looses when moved

- 드라코들은 이제 아래 종류의 갑옷을 입을 수 있음. 
  - All dracos can wear armour listed below
  - 로브 
    - Robe
  - 가죽 갑옷 
    - Leather armour
  - 트롤 가죽 갑옷 
    - Troll leather armour
  - 모든 종류의 용 비늘 갑옷
     - all kinds of dragon scale

- 드라코들은 갑옷술을 수련 할 수 있음. 
  - All draco can train armour skill.
  - 적성은 -3.
    - Aptitude is -3.

- 드라코들은 시작할 때 뒤틀린 몸 변이를 가짐. 
  - All draco have deform mutation at start.

- 힐완드 복구에 따라 포션 힐 불가 변이가 디바이스 힐 불가로 변경.
  - Rollback no potion heal mutation to no device heal.
  - 이전의 해당 변이와 마찬가지로 완드로 인한 힐링도 불가능.
    - No device heal prevents heal from potions and wands.

### Removed


### 0.25 Featrue
- 갑옷 장착시 AC를 보여주는 인터페이스 추가
  - Improve armour AC change descriptions
  
- 독 중첩단계에 따른 타일 이펙트 추가
  - can see poison level mons and player
  
- 에어스트라이크는 주변의 빈공간의 수만큼 데미지가 증가됨
  - Airstrike damage now scales so it's greater the more unoccupied squares there are surrounding the target.

- 오조크브의 냉장고의 데미지 33%증가되고 시전자에게 데미지를 주지않음
  - Ozocubu's Refrigeration does 33% more damage on-average and no longer harms the caster
  
- 베놈 메이지의 기본책인 The Young Poisoner's Handbook은 이제 이그나이트 포이즌을 들고 시작함
  - The Young Poisoner's Handbook now contains Ignite Poison.
  
  
  
[Unreleased]: https://github.com/kimjoy2002/crawl/compare/0.24.1...HEAD
