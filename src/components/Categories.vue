<template>
  <div>
    copy code
  </div>
  <!-- <div class="row">
    <div class="row__inner">

      <div class="tile">
        <div class="tile__media">
          <img class="tile__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/70390/show-1.jpg" alt=""  />
        </div>
        <div class="tile__details">
          <div class="tile__title">
            Top Gear
          </div>
        </div>
      </div>

      <div class="tile">
        <div class="tile__media">
          <img class="tile__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/70390/show-2.jpg" alt=""  />
        </div>
        <div class="tile__details">
          <div class="tile__title">
            Top Gear
          </div>
        </div>
      </div>

      <div class="tile">
        <div class="tile__media">
          <img class="tile__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/70390/show-3.jpg" alt=""  />
        </div>
        <div class="tile__details">
          <div class="tile__title">
            Top Gear
          </div>
        </div>
      </div>

      <div class="tile">
        <div class="tile__media">
          <img class="tile__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/70390/show-4.jpg" alt=""  />
        </div>
        <div class="tile__details">
          <div class="tile__title">
            Top Gear
          </div>
        </div>
      </div>

      <div class="tile">
        <div class="tile__media">
          <img class="tile__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/70390/show-5.jpg" alt=""  />
        </div>
        <div class="tile__details">
          <div class="tile__title">
            Top Gear
          </div>
        </div>
      </div>

      <div class="tile">
        <div class="tile__media">
          <img class="tile__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/70390/show-6.jpg" alt=""  />
        </div>
        <div class="tile__details">
          <div class="tile__title">
            Top Gear
          </div>
        </div>
      </div>

    </div>
  </div> -->
</template>

<script>
export default {

};
</script>

<style lang='scss'>
// .contain
//   width: 100%

// .row
//   overflow: scroll
//   width: 100%

// .row__inner
//   transition: $duration transform
//   font-size: 0
//   white-space: nowrap
//   margin: ($tileHeight / 2) 0
//   padding-bottom: 10px // Account for OS X scroll bar

// .tile
//   position: relative
//   display: inline-block
//   width: $tileWidth
//   height: $tileHeight
//   margin-right: 10px
//   font-size: 20px
//   cursor: pointer
//   transition: $duration all
//   transform-origin: center left

// .tile__img
//   width: $tileWidth
//   height: $tileHeight
//   object-fit: cover

// .tile__details
//   position: absolute
//   bottom: 0
//   left: 0
//   right: 0
//   top: 0
//   font-size: 10px
//   opacity: 0
//   background: linear-gradient(to top, rgba(0,0,0,0.9) 0%, rgba(0,0,0,0) 100%)
//   transition: $duration opacity

//   &:after
//   &:before
//     content: ''
//     position absolute
//     top: 50%
//     left: 50%
//     display: black

//   &:after
//     margin-top: (-($iconSize / 2))
//     margin-left: (-($iconSize / 2))
//     width: $iconSize
//     height: $iconSize
//     border: 3px solid #ecf0f1
//     line-height: $iconSize
//     text-align: center
//     border-radius: 100%
//     background: rgba(0,0,0,0.5)
//     z-index: 1

//   &:before
//     content: '▶'
//     left: 0
//     width: 100%
//     font-size: 30px
//     margin-left: 7px
//     margin-top: -18px
//     text-align: center
//     z-index: 2

//   .tile:hover &
//     opacity: 1

// .tile__title
//   position absolute
//   bottom: 0
//   padding: 10px

// // *
// // * Hover effects
// // *

// // We assume when you hover .row, you're also hovering a .tile
// // First, move the whole row towards the left
// .row__inner:hover
//   transform: translate3d($moveLeft, 0, 0)

// .row__inner:hover .tile

//   // Fade out every tile
//   opacity: .3

//   // And then grow the current tile and make it opaque again
//   &:hover
//     transform: scale($growFactor)
//     opacity: 1

// // And finally move all tiles right of the current tile to the right,
// // so its flush against the hovered tile
// .tile:hover ~ .tile
//   transform: translate3d($moveRight, 0, 0)
</style>
