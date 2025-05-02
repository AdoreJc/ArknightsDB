# Act1AutoChessCharSelectPoolViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `ActivityAutoChessVerify1Data m_actData`

- `RarityRank m_rarityLimit`

- `Int32 m_localInstIdNum`


## Methods

- `Int32 _AllocInstId()`

- `Boolean _ValidChar(PlayerCharacter)`

- `Boolean _UsedForChess(PlayerCharacter)`

- `Void _AddUnusedBackupChar(Act1VAutoChessCharShopChessData, HashSet`1)`

- `Act1VAutoChessCharSelectCardViewModel _CreateBackupChar(Int32, Act1VAutoChessCharShopChessData, Act1VAutoChessCharShopChessData, Act1VAutoChessCharShopChessData)`

- `Void <>xLuaBaseProxy_Reset(TemplateCharSelectModelResetData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1AutoChessCharSelectPoolViewModel : CommonCharSelectPoolViewModel
{
	private ActivityAutoChessVerify1Data m_actData; // 0x60
	private RarityRank m_rarityLimit; // 0x68
	private Int32 m_localInstIdNum; // 0x6c
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0__AllocInstId; // 0x8
	private static DelegateBridge __Hotfix0__ValidChar; // 0x10
	private static DelegateBridge __Hotfix0__UsedForChess; // 0x18
	private static DelegateBridge __Hotfix0__AddUnusedBackupChar; // 0x20
	private static DelegateBridge __Hotfix0__CreateBackupChar; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x338bb2c VA: 0x75959a3b2c
	public override Void Reset(TemplateCharSelectModelResetData data) { }
	// RVA: 0x338c56c VA: 0x75959a456c
	private Int32 _AllocInstId() { }
	// RVA: 0x338c3c8 VA: 0x75959a43c8
	private Boolean _ValidChar(PlayerCharacter playerChar) { }
	// RVA: 0x338caf0 VA: 0x75959a4af0
	private Boolean _UsedForChess(PlayerCharacter playerChar) { }
	// RVA: 0x338c7c0 VA: 0x75959a47c0
	private Void _AddUnusedBackupChar(Act1VAutoChessCharShopChessData forChess, HashSet`1 alreadyAdd) { }
	// RVA: 0x338c5dc VA: 0x75959a45dc
	private Act1VAutoChessCharSelectCardViewModel _CreateBackupChar(Int32 instId, Act1VAutoChessCharShopChessData forChess, Act1VAutoChessCharShopChessData originChess, Act1VAutoChessCharShopChessData inChess) { }
	// RVA: 0x338cd2c VA: 0x75959a4d2c
	public Void .ctor() { }
	// RVA: 0x338cd9c VA: 0x75959a4d9c
	private Void <>xLuaBaseProxy_Reset(TemplateCharSelectModelResetData P0) { }
}
```