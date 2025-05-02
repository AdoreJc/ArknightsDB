# CutinChannel

**Namespace:** `Torappu.UI`


## Fields

- `CutinImageElement _leftChar`

- `CutinImageElement _middleChar`

- `CutinImageElement _rightChar`

- `CutinImageElement _imgBg`

- `Transform _maskContainer`

- `CanvasGroup _group`

- `CutinAVGCharacterSlot _slotPrefab`

- `Transform _charSlotContainer`

- `Transform _decoContainer`

- `Sequence m_charSeq`

- `Sequence m_bgSeq`

- `Sequence m_avatarSeq`

- `CutinTemplate m_maskTemplate`

- `ILoadAsset m_assetLoader`

- `CutinAVGCharacterSlot m_cachedCharslot`

- `Int32 m_channelId`


## Methods

- `Void _ProcessElement(CutinParam, Sequence, Action)`

- `CutinElement _GetImgElementByParam(CutinParam)`

- `Void _KillCharAnim()`

- `Void OnCutinBegin(CutinParam, CutinChannelOptions, Action)`

- `Void OnCutinUpdate(CutinParam, Action)`

- `Void OnCutinEnd(CutinParam, Action)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Sequence _EnsureCharSequence()`

- `Sequence _EnsureBgSequence()`

- `Sequence _EnsureAvatarSequence()`

- `StencilChannel _GetStencilChannel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CutinChannel : MonoBehaviour, IReusable, IHotfixable
{
	private CutinImageElement _leftChar; // 0x18
	private CutinImageElement _middleChar; // 0x20
	private CutinImageElement _rightChar; // 0x28
	private CutinImageElement _imgBg; // 0x30
	private Transform _maskContainer; // 0x38
	private CanvasGroup _group; // 0x40
	private CutinAVGCharacterSlot _slotPrefab; // 0x48
	private Transform _charSlotContainer; // 0x50
	private Transform _decoContainer; // 0x58
	private const String LEFT_SLOT; // 0x0
	private const String LEFT_SLOT_SHORT; // 0x0
	private const String RIGHT_SLOT; // 0x0
	private const String RIGHT_SLOT_SHORT; // 0x0
	private const String MIDDLE_SLOT; // 0x0
	private const String MIDDLE_SLOT_SHORT; // 0x0
	private static readonly StencilChannel[] stencilChannels; // 0x0
	private Sequence m_charSeq; // 0x60
	private Sequence m_bgSeq; // 0x68
	private Sequence m_avatarSeq; // 0x70
	private CutinTemplate m_maskTemplate; // 0x78
	private ILoadAsset m_assetLoader; // 0x80
	private CutinAVGCharacterSlot m_cachedCharslot; // 0x88
	private Int32 m_channelId; // 0x90
	private static DelegateBridge __Hotfix0__ProcessElement; // 0x8
	private static DelegateBridge __Hotfix0__GetImgElementByParam; // 0x10
	private static DelegateBridge __Hotfix0__KillCharAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnCutinBegin; // 0x20
	private static DelegateBridge __Hotfix0_OnCutinUpdate; // 0x28
	private static DelegateBridge __Hotfix0_OnCutinEnd; // 0x30
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x38
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x40
	private static DelegateBridge __Hotfix0__EnsureCharSequence; // 0x48
	private static DelegateBridge __Hotfix0__EnsureBgSequence; // 0x50
	private static DelegateBridge __Hotfix0__EnsureAvatarSequence; // 0x58
	private static DelegateBridge __Hotfix0__GetStencilChannel; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x216a6a4 VA: 0x75947826a4
	private Void _ProcessElement(CutinParam param, Sequence elementSeq, Action cb) { }
	// RVA: 0x216aab4 VA: 0x7594782ab4
	private CutinElement _GetImgElementByParam(CutinParam param) { }
	// RVA: 0x216ae68 VA: 0x7594782e68
	private Void _KillCharAnim() { }
	// RVA: 0x216af08 VA: 0x7594782f08
	public Void OnCutinBegin(CutinParam cutin, CutinChannelOptions options, Action cb) { }
	// RVA: 0x216b1c8 VA: 0x75947831c8
	public Void OnCutinUpdate(CutinParam cutin, Action cb) { }
	// RVA: 0x216b5a0 VA: 0x75947835a0
	public Void OnCutinEnd(CutinParam cutin, Action cb) { }
	// RVA: 0x216b6ac VA: 0x75947836ac
	public Void OnAllocate() { }
	// RVA: 0x216b720 VA: 0x7594783720
	public Void OnRecycle() { }
	// RVA: 0x216b338 VA: 0x7594783338
	private Sequence _EnsureCharSequence() { }
	// RVA: 0x216b3ec VA: 0x75947833ec
	private Sequence _EnsureBgSequence() { }
	// RVA: 0x216b4a0 VA: 0x75947834a0
	private Sequence _EnsureAvatarSequence() { }
	// RVA: 0x216ad10 VA: 0x7594782d10
	private StencilChannel _GetStencilChannel(Int32 channelIdx) { }
	// RVA: 0x216b830 VA: 0x7594783830
	public Void .ctor() { }
	// RVA: 0x216b8b0 VA: 0x75947838b0
	private static Void .cctor() { }
}
```