# SoftMask

**Namespace:** `SoftMasking`


## Fields

- `Shader _defaultShader`

- `Shader _defaultETC1Shader`

- `MaskSource _source`

- `RectTransform _separateMask`

- `Sprite _sprite`

- `BorderMode _spriteBorderMode`

- `Texture2D _texture`

- `Rect _textureUVRect`

- `Color _channelWeights`

- `Single _raycastThreshold`

- `MaterialReplacements _materials`

- `MaterialParameters _parameters`

- `Sprite _lastUsedSprite`

- `Boolean _maskingWasEnabled`

- `Boolean _destroyed`

- `Boolean _dirty`

- `RectTransform _maskTransform`

- `Graphic _graphic`

- `Canvas _canvas`


## Properties

- `Shader defaultShader`

- `Shader defaultETC1Shader`

- `MaskSource source`

- `RectTransform separateMask`

- `Sprite sprite`

- `BorderMode spriteBorderMode`

- `Texture2D texture`

- `Rect textureUVRect`

- `Color channelWeights`

- `Single raycastThreshold`

- `Boolean isMaskingEnabled`

- `RectTransform maskTransform`

- `Canvas canvas`

- `Boolean isBasedOnGraphic`


## Methods

- `Shader get_defaultShader()`

- `Void set_defaultShader(Shader)`

- `Shader get_defaultETC1Shader()`

- `Void set_defaultETC1Shader(Shader)`

- `MaskSource get_source()`

- `Void set_source(MaskSource)`

- `RectTransform get_separateMask()`

- `Void set_separateMask(RectTransform)`

- `Sprite get_sprite()`

- `Void set_sprite(Sprite)`

- `BorderMode get_spriteBorderMode()`

- `Void set_spriteBorderMode(BorderMode)`

- `Texture2D get_texture()`

- `Void set_texture(Texture2D)`

- `Rect get_textureUVRect()`

- `Void set_textureUVRect(Rect)`

- `Color get_channelWeights()`

- `Void set_channelWeights(Color)`

- `Single get_raycastThreshold()`

- `Void set_raycastThreshold(Single)`

- `Boolean get_isMaskingEnabled()`

- `Errors PollErrors()`

- `Boolean IsRaycastLocationValid(Vector2, Camera)`

- `Void OnTransformChildrenChanged()`

- `RectTransform get_maskTransform()`

- `Canvas get_canvas()`

- `Boolean get_isBasedOnGraphic()`

- `Void OnGraphicDirty()`

- `Void FindGraphic()`

- `Canvas NearestEnabledCanvas()`

- `Void UpdateMaskParameters()`

- `Void SpawnMaskablesInChildren(Transform)`

- `Void InvalidateChildren()`

- `Void NotifyChildrenThatMaskMightChanged()`

- `Void ForEachChildMaskable(Action`1)`

- `Void DestroyMaterials()`

- `Void CalculateMaskParameters()`

- `BorderMode ToBorderMode(Type)`

- `Void CalculateImageBased(Image)`

- `Void CalculateRawImageBased(RawImage)`

- `Void CalculateSpriteBased(Sprite, BorderMode)`

- `Void CalculateTextureBased(Texture2D, Rect)`

- `Void CalculateSolidFill()`

- `Void FillCommonParameters()`

- `Single GraphicToCanvasScale(Sprite)`

- `Matrix4x4 WorldToMask()`

- `Vector4 LocalMaskRect(Vector4)`

- `Vector2 MaskRepeat(Sprite, Vector4)`

- `Void WarnIfDefaultShaderIsNotSet()`

- `Void WarnSpriteErrors(Errors)`

- `Void Set(ref, T)`

- `Void SetShader(ref, Shader, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : SoftMasking
public class SoftMask : UIBehaviour, ISoftMask, ICanvasRaycastFilter
{
	private Shader _defaultShader; // 0x18
	private Shader _defaultETC1Shader; // 0x20
	private MaskSource _source; // 0x28
	private RectTransform _separateMask; // 0x30
	private Sprite _sprite; // 0x38
	private BorderMode _spriteBorderMode; // 0x40
	private Texture2D _texture; // 0x48
	private Rect _textureUVRect; // 0x50
	private Color _channelWeights; // 0x60
	private Single _raycastThreshold; // 0x70
	private MaterialReplacements _materials; // 0x78
	private MaterialParameters _parameters; // 0x80
	private Sprite _lastUsedSprite; // 0x130
	private Boolean _maskingWasEnabled; // 0x138
	private Boolean _destroyed; // 0x139
	private Boolean _dirty; // 0x13a
	private RectTransform _maskTransform; // 0x140
	private Graphic _graphic; // 0x148
	private Canvas _canvas; // 0x150
	private static readonly Rect DefaultUVRect; // 0x0
	private static readonly List`1 s_masks; // 0x10
	private static readonly List`1 s_maskables; // 0x18

	public Shader defaultShader { get; set; }
	public Shader defaultETC1Shader { get; set; }
	public MaskSource source { get; set; }
	public RectTransform separateMask { get; set; }
	public Sprite sprite { get; set; }
	public BorderMode spriteBorderMode { get; set; }
	public Texture2D texture { get; set; }
	public Rect textureUVRect { get; set; }
	public Color channelWeights { get; set; }
	public Single raycastThreshold { get; set; }
	public Boolean isMaskingEnabled { get; }
	private RectTransform maskTransform { get; }
	private Canvas canvas { get; }
	private Boolean isBasedOnGraphic { get; }
	private Boolean SoftMasking.ISoftMask.isAlive { get; }

	// RVA: 0x2b4deec VA: 0x7595165eec
	public Void .ctor() { }
	// RVA: 0x2b4e0c4 VA: 0x75951660c4
	public Shader get_defaultShader() { }
	// RVA: 0x2b4e0cc VA: 0x75951660cc
	public Void set_defaultShader(Shader value) { }
	// RVA: 0x2b4e1a8 VA: 0x75951661a8
	public Shader get_defaultETC1Shader() { }
	// RVA: 0x2b4e1b0 VA: 0x75951661b0
	public Void set_defaultETC1Shader(Shader value) { }
	// RVA: 0x2b4e1c4 VA: 0x75951661c4
	public MaskSource get_source() { }
	// RVA: 0x2b4e1cc VA: 0x75951661cc
	public Void set_source(MaskSource value) { }
	// RVA: 0x2b4e238 VA: 0x7595166238
	public RectTransform get_separateMask() { }
	// RVA: 0x2b4e240 VA: 0x7595166240
	public Void set_separateMask(RectTransform value) { }
	// RVA: 0x2b4e30c VA: 0x759516630c
	public Sprite get_sprite() { }
	// RVA: 0x2b4e314 VA: 0x7595166314
	public Void set_sprite(Sprite value) { }
	// RVA: 0x2b4e3c0 VA: 0x75951663c0
	public BorderMode get_spriteBorderMode() { }
	// RVA: 0x2b4e3c8 VA: 0x75951663c8
	public Void set_spriteBorderMode(BorderMode value) { }
	// RVA: 0x2b4e434 VA: 0x7595166434
	public Texture2D get_texture() { }
	// RVA: 0x2b4e43c VA: 0x759516643c
	public Void set_texture(Texture2D value) { }
	// RVA: 0x2b4e4e8 VA: 0x75951664e8
	public Rect get_textureUVRect() { }
	// RVA: 0x2b4e4f4 VA: 0x75951664f4
	public Void set_textureUVRect(Rect value) { }
	// RVA: 0x2b4e5a8 VA: 0x75951665a8
	public Color get_channelWeights() { }
	// RVA: 0x2b4e5b4 VA: 0x75951665b4
	public Void set_channelWeights(Color value) { }
	// RVA: 0x2b4e688 VA: 0x7595166688
	public Single get_raycastThreshold() { }
	// RVA: 0x2b4e690 VA: 0x7595166690
	public Void set_raycastThreshold(Single value) { }
	// RVA: 0x2b4e698 VA: 0x7595166698
	public Boolean get_isMaskingEnabled() { }
	// RVA: 0x2b4e7b0 VA: 0x75951667b0
	public Errors PollErrors() { }
	// RVA: 0x2b4e7e4 VA: 0x75951667e4
	public Boolean IsRaycastLocationValid(Vector2 sp, Camera cam) { }
	// RVA: 0x2b4ebf8 VA: 0x7595166bf8
	protected override Void Start() { }
	// RVA: 0x2b4ecc8 VA: 0x7595166cc8
	protected override Void OnEnable() { }
	// RVA: 0x2b4f0cc VA: 0x75951670cc
	protected override Void OnDisable() { }
	// RVA: 0x2b4f224 VA: 0x7595167224
	protected override Void OnDestroy() { }
	// RVA: 0x2b4f248 VA: 0x7595167248
	protected virtual Void LateUpdate() { }
	// RVA: 0x2b4f2d8 VA: 0x75951672d8
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x2b4f3b4 VA: 0x75951673b4
	protected override Void OnDidApplyAnimationProperties() { }
	// RVA: 0x2b4f3d4 VA: 0x75951673d4
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x2b4f404 VA: 0x7595167404
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x2b4f438 VA: 0x7595167438
	private Void OnTransformChildrenChanged() { }
	// RVA: 0x2b4e9bc VA: 0x75951669bc
	private RectTransform get_maskTransform() { }
	// RVA: 0x2b4e720 VA: 0x7595166720
	private Canvas get_canvas() { }
	// RVA: 0x2b4f508 VA: 0x7595167508
	private Boolean get_isBasedOnGraphic() { }
	// RVA: 0x2b4f518 VA: 0x7595167518
	private Boolean SoftMasking.ISoftMask.get_isAlive() { }
	// RVA: 0x2b4f58c VA: 0x759516758c
	private Material SoftMasking.ISoftMask.GetReplacement(Material original) { }
	// RVA: 0x2b4f5a4 VA: 0x75951675a4
	private Void SoftMasking.ISoftMask.ReleaseReplacement(Material replacement) { }
	// RVA: 0x2b4f5bc VA: 0x75951675bc
	private Void SoftMasking.ISoftMask.UpdateTransformChildren(Transform transform) { }
	// RVA: 0x2b4f5c0 VA: 0x75951675c0
	private Void OnGraphicDirty() { }
	// RVA: 0x2b4ee24 VA: 0x7595166e24
	private Void FindGraphic() { }
	// RVA: 0x2b4f450 VA: 0x7595167450
	private Canvas NearestEnabledCanvas() { }
	// RVA: 0x2b4efa4 VA: 0x7595166fa4
	private Void UpdateMaskParameters() { }
	// RVA: 0x2b4ed14 VA: 0x7595166d14
	private Void SpawnMaskablesInChildren(Transform root) { }
	// RVA: 0x2b4f820 VA: 0x7595167820
	private Void InvalidateChildren() { }
	// RVA: 0x2b4efe0 VA: 0x7595166fe0
	private Void NotifyChildrenThatMaskMightChanged() { }
	// RVA: 0x2b4f90c VA: 0x759516790c
	private Void ForEachChildMaskable(Action`1 f) { }
	// RVA: 0x2b4f20c VA: 0x759516720c
	private Void DestroyMaterials() { }
	// RVA: 0x2b4f5d8 VA: 0x75951675d8
	private Void CalculateMaskParameters() { }
	// RVA: 0x2b50148 VA: 0x7595168148
	private BorderMode ToBorderMode(Type imageType) { }
	// RVA: 0x2b4fae4 VA: 0x7595167ae4
	private Void CalculateImageBased(Image image) { }
	// RVA: 0x2b4fb1c VA: 0x7595167b1c
	private Void CalculateRawImageBased(RawImage image) { }
	// RVA: 0x2b4fbfc VA: 0x7595167bfc
	private Void CalculateSpriteBased(Sprite sprite, BorderMode borderMode) { }
	// RVA: 0x2b50588 VA: 0x7595168588
	private static Vector4 AdjustBorders(Vector4 border, Vector4 rect) { }
	// RVA: 0x2b50090 VA: 0x7595168090
	private Void CalculateTextureBased(Texture2D texture, Rect uvRect) { }
	// RVA: 0x2b4fb94 VA: 0x7595167b94
	private Void CalculateSolidFill() { }
	// RVA: 0x2b50348 VA: 0x7595168348
	private Void FillCommonParameters() { }
	// RVA: 0x2b5049c VA: 0x759516849c
	private Single GraphicToCanvasScale(Sprite sprite) { }
	// RVA: 0x2b50690 VA: 0x7595168690
	private Matrix4x4 WorldToMask() { }
	// RVA: 0x2b4ea98 VA: 0x7595166a98
	private Vector4 LocalMaskRect(Vector4 border) { }
	// RVA: 0x2b505d4 VA: 0x75951685d4
	private Vector2 MaskRepeat(Sprite sprite, Vector4 centralPart) { }
	// RVA: 0x2b4ec14 VA: 0x7595166c14
	private Void WarnIfDefaultShaderIsNotSet() { }
	// RVA: 0x2b5027c VA: 0x759516827c
	private Void WarnSpriteErrors(Errors errors) { }
	// RVA: 0x VA: 0x0
	private Void Set(ref T field, T value) { }
	// RVA: 0x2b4e0e0 VA: 0x75951660e0
	private Void SetShader(ref Shader field, Shader value, Boolean warnIfNotSet) { }
	// RVA: 0x2b50768 VA: 0x7595168768
	private static Void .cctor() { }
	// RVA: 0x2b50888 VA: 0x7595168888
	private Void <.ctor>b__19_0(Material m) { }
}
```