<template>
  <div class="container">
    <Nav />
    <div class="img_box">
      <div class="img__main_box">
        <div class="upper_slogen">
          THIS IS A SMALLER POSTER.
        </div>

        <div class="lower_slogen">
          this is a larger poster.
        </div>

        <div class="searchdiv">
          <div class="searchbar">
            <input
              class="search_text"
              type="text"
              placeholder="输入搜索内容..."
            />
            <div class="search_btn">
              <button>search</button>
            </div>
          </div>

          <div id="cutline1"></div>

          <button id="advanced_search">高级搜索</button>
        </div>
      </div>

      <div id="cutline2"></div>

      <div class="img__msg_box">
        <span id="title">已收录文献</span>
        <div id="statistic">
          <span id="high">146</span><span id="low">146</span>
        </div>
      </div>
    </div>

    <div class="main_content">
      <div class="left_box">
        <div class="box_info">
          <span id="title">热门文献</span>
          <span id="degree">热度</span>
        </div>
        <div class="left_box__content">
          <div class="left_box__item">
            <span>1</span>
            <span>啊！海军</span>
            <span>300000000</span>
          </div>
          <div class="left_box__item">
            <span>2</span>
            <span>啊！海军</span>
            <span>0</span>
          </div>
          <div class="left_box__item">
            <span>3</span>
            <span>啊！海军</span>
            <span>30</span>
          </div>
          <div class="left_box__item">
            <span>4</span>
            <span>啊！海军</span>
            <span>300</span>
          </div>
          <div class="left_box__item">
            <span>5</span>
            <span>啊！海军</span>
            <span>3000</span>
          </div>
          <div class="left_box__item">
            <span>6</span>
            <span>啊！海军</span>
            <span>30000</span>
          </div>
          <div class="left_box__item">
            <span>7</span>
            <span>啊！海军</span>
            <span>3000000</span>
          </div>
          <div class="left_box__item">
            <span>8</span>
            <span>啊！海军</span>
            <span>30000000</span>
          </div>
          <div class="left_box__item">
            <span>9</span>
            <span>啊！海军</span>
            <span>300000000</span>
          </div>
          <div class="left_box__item">
            <span>10</span>
            <span>啊！海军</span>
            <span>3000W</span>
          </div>
        </div>
      </div>

      <div id="cutline3"></div>

      <div class="right_box">
        <div class="box_info">
          <span id="title">最新动态</span>
        </div>
        <div class="rigth_box__content">
          <div class="right_box__inner paper_box">
            <div class="inner_header">
              <span id="inner_title">期刊论文</span>
              <input class="more_btn" type="button" value="more" />
            </div>
            <div class="inner_content">
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
            </div>
          </div>
          <div class="right_box__inner research_box">
            <div class="inner_header">
              <span id="inner_title">科研专利</span>
              <input class="more_btn" type="button" value="more" />
            </div>
            <div class="inner_content">
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
              <div class="inner_item">
                <div id="linesign"></div>
                <span>啊！海军</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <span>footer</span>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Nav from "@/components/Nav.vue";

@Options({
  components: {
    Nav,
  },
})
export default class Home extends Vue {}
</script>

<style>
@import "../assets/css/global.css";
@import "../assets/css/home_frontarea.css";
@import "../assets/css/home_mainarea.css";
</style>
