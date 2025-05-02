# Act12D6GameEndViewModel

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Boolean isDead`

- `String lastZoneName`

- `String lastZoneEndingDesc`

- `String endingId`

- `String endingBackgroundId`

- `String endingName`

- `String endingDesc`

- `String nickName`

- `Int64 beginTs`

- `Int64 endTs`

- `Int32 totalSeconds`

- `Int32 passedZoneCnt`

- `Int32 moveCnt`

- `Int32 normalBattleCnt`

- `Int32 eliteBattleCnt`

- `Int32 bossBattleCnt`

- `Int32 relicCnt`

- `Int32 charCnt`

- `Int32 passedZoneScore`

- `Int32 moveScore`

- `Int32 normalBattleScore`

- `Int32 eliteBattleScore`

- `Int32 bossBattleScore`

- `Int32 relicScore`

- `Int32 charScore`

- `String modeId`

- `String modeName`

- `Single modeFactor`

- `Int32 totalScore`

- `String outBuffTokenId`

- `String outBuffTokenName`

- `Sprite outBuffTokenIconSprite`

- `Single outbuffTokenFactor`

- `Int32 outBuffTokenCnt`

- `String milestoneTokenId`

- `String milestoneTokenName`

- `Sprite milestoneTokenIconSprite`

- `Single milestoneTokenFactor`

- `Int32 milestoneTokenCnt`

- `RoguelikeRelicViewModel initRelic`


## Methods

- `Void _LoadRelics()`

- `Void _LoadUnlockedRelics(PlayerRoguelikeRecord)`

- `Int32 _CompareChar(RoguelikeCharCardViewModel, RoguelikeCharCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6GameEndViewModel : IHotfixable
{
	public Boolean isDead; // 0x10
	public String lastZoneName; // 0x18
	public String lastZoneEndingDesc; // 0x20
	public String endingId; // 0x28
	public String endingBackgroundId; // 0x30
	public String endingName; // 0x38
	public String endingDesc; // 0x40
	public String nickName; // 0x48
	public Int64 beginTs; // 0x50
	public Int64 endTs; // 0x58
	public Int32 totalSeconds; // 0x60
	public Int32 passedZoneCnt; // 0x64
	public Int32 moveCnt; // 0x68
	public Int32 normalBattleCnt; // 0x6c
	public Int32 eliteBattleCnt; // 0x70
	public Int32 bossBattleCnt; // 0x74
	public Int32 relicCnt; // 0x78
	public Int32 charCnt; // 0x7c
	public Int32 passedZoneScore; // 0x80
	public Int32 moveScore; // 0x84
	public Int32 normalBattleScore; // 0x88
	public Int32 eliteBattleScore; // 0x8c
	public Int32 bossBattleScore; // 0x90
	public Int32 relicScore; // 0x94
	public Int32 charScore; // 0x98
	public String modeId; // 0xa0
	public String modeName; // 0xa8
	public Single modeFactor; // 0xb0
	public Int32 totalScore; // 0xb4
	public String outBuffTokenId; // 0xb8
	public String outBuffTokenName; // 0xc0
	public Sprite outBuffTokenIconSprite; // 0xc8
	public Single outbuffTokenFactor; // 0xd0
	public Int32 outBuffTokenCnt; // 0xd4
	public String milestoneTokenId; // 0xd8
	public String milestoneTokenName; // 0xe0
	public Sprite milestoneTokenIconSprite; // 0xe8
	public Single milestoneTokenFactor; // 0xf0
	public Int32 milestoneTokenCnt; // 0xf4
	public RoguelikeRelicViewModel initRelic; // 0xf8
	public List`1 relics; // 0x100
	public List`1 chars; // 0x108
	public List`1 unlockedModes; // 0x110
	public List`1 unlockedInitRelics; // 0x118
	public List`1 unlockedRelics; // 0x120
	private static DelegateBridge __Hotfix0__LoadRelics; // 0x0
	private static DelegateBridge __Hotfix0__LoadUnlockedRelics; // 0x8
	private static DelegateBridge __Hotfix0__CompareChar; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x347bd60 VA: 0x7595a93d60
	private Void _LoadRelics() { }
	// RVA: 0x347bf2c VA: 0x7595a93f2c
	private Void _LoadUnlockedRelics(PlayerRoguelikeRecord record) { }
	// RVA: 0x347c02c VA: 0x7595a9402c
	private Int32 _CompareChar(RoguelikeCharCardViewModel lhs, RoguelikeCharCardViewModel rhs) { }
	// RVA: 0x347bba0 VA: 0x7595a93ba0
	public Void .ctor() { }
}
```