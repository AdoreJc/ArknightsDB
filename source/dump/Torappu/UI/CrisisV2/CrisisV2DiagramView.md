# CrisisV2DiagramView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIScaler _dimensionPartScaler`

- `UIAnimationLocation _battleSettleEnterAnim`

- `UIAnimationLocation _battleSettleNewRecordAnim`

- `Single _splitLineMinWidth`

- `Single _currentHeightDelta`

- `Single _baseHeightDelta`

- `Boolean m_hasInited`

- `Tween m_animTween`


## Methods

- `Void Render(CrisisV2DiagramInput)`

- `Void ResetDiagram()`

- `Void PlayBattleSettleEnterAnim()`

- `Void PlayBattleSettleNewRecordAnim()`

- `Void OnDestroy()`

- `Void _InitIfNot(StyleConfig)`

- `String _GetDescIconId(DescAndScoreStyle, Int32)`

- `DimensionInput _GenerateDimensionInput(CrisisV2DiagramInput, Int32)`

- `DescAndScoreInput _GenerateDescAndScoreInput(CrisisV2DiagramInput, Int32)`

- `Void _StopAnim()`

- `Void _PlayDiagramAnim(UIAnimationLocation)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2DiagramView : MonoBehaviour, IHotfixable
{
	private const String DIAGRAM_ICON_ACHIEVE_FORMAT; // 0x0
	private const String DIAGRAM_ICON_BATTLE_SETTLE_FORMAT; // 0x0
	private List`1 _bgScoreHolders; // 0x18
	private List`1 _dimensions; // 0x20
	private UIScaler _dimensionPartScaler; // 0x28
	private UIAnimationLocation _battleSettleEnterAnim; // 0x30
	private UIAnimationLocation _battleSettleNewRecordAnim; // 0x40
	private List`1 _splitLines; // 0x50
	private Single _splitLineMinWidth; // 0x58
	private Single _currentHeightDelta; // 0x5c
	private Single _baseHeightDelta; // 0x60
	private Boolean m_hasInited; // 0x64
	private List`1 m_descAndScoreItems; // 0x68
	private Tween m_animTween; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetDiagram; // 0x8
	private static DelegateBridge __Hotfix0_PlayBattleSettleEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0_PlayBattleSettleNewRecordAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__GetDescIconId; // 0x30
	private static DelegateBridge __Hotfix0__GenerateDimensionInput; // 0x38
	private static DelegateBridge __Hotfix0__GenerateDescAndScoreInput; // 0x40
	private static DelegateBridge __Hotfix0__StopAnim; // 0x48
	private static DelegateBridge __Hotfix0__PlayDiagramAnim; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2bce9b0 VA: 0x75951e69b0
	public Void Render(CrisisV2DiagramInput input) { }
	// RVA: 0x2bcf3ec VA: 0x75951e73ec
	public Void ResetDiagram() { }
	// RVA: 0x2bcf56c VA: 0x75951e756c
	public Void PlayBattleSettleEnterAnim() { }
	// RVA: 0x2bcf6c8 VA: 0x75951e76c8
	public Void PlayBattleSettleNewRecordAnim() { }
	// RVA: 0x2bcf734 VA: 0x75951e7734
	public Void OnDestroy() { }
	// RVA: 0x2bcebec VA: 0x75951e6bec
	private Void _InitIfNot(StyleConfig styleConfig) { }
	// RVA: 0x2bcf79c VA: 0x75951e779c
	private String _GetDescIconId(DescAndScoreStyle style, Int32 index) { }
	// RVA: 0x2bcf010 VA: 0x75951e7010
	private DimensionInput _GenerateDimensionInput(CrisisV2DiagramInput diagramInput, Int32 index) { }
	// RVA: 0x2bcf258 VA: 0x75951e7258
	private DescAndScoreInput _GenerateDescAndScoreInput(CrisisV2DiagramInput diagramInput, Int32 index) { }
	// RVA: 0x2bcf4bc VA: 0x75951e74bc
	private Void _StopAnim() { }
	// RVA: 0x2bcf5d8 VA: 0x75951e75d8
	private Void _PlayDiagramAnim(UIAnimationLocation anim) { }
	// RVA: 0x2bcf8b0 VA: 0x75951e78b0
	public Void .ctor() { }
}
```