---
layout: default
title:  "[Phụ lục 11] Biểu đồ từ loại của tiếng Hàn"
nav_order: 12
parent: Phụ lục
---

# [Phụ lục 11] Biểu đồ từ loại của tiếng Hàn

<div id="tree">
  <div class="branch">
    <div class="entry"><span>Nhóm danh từ</span>
      <div class="branch">
        <div class="entry"><span>Danh từ</span>          
        </div>
        <div class="entry"><span>Đại từ</span>
        </div>
      </div>
    </div>
        <div class="entry"><span>Nhóm vị từ</span>
      <div class="branch">
        <div class="entry"><span>Động từ</span>          
        </div>
        <div class="entry"><span>Tính từ</span>
        </div>
        <div class="entry"><span>Vị từ 이다</span>
        </div>
      </div>
    </div>
    <div class="entry"><span>Nhóm từ quan hệ</span>
      <div class="branch">
        <div class="entry"><span>Trợ từ</span>          
        </div>
        <div class="entry"><span>Vĩ tố</span>
          <div class="branch">
            <div class="entry"><span>Vĩ tố kết thúc câu</span>     
            </div>
            <div class="entry"><span>Vĩ tố liên kết</span>
            </div>
            <div class="entry"><span>Vĩ tố tiền kết thúc</span>
            </div>
            <div class="entry"><span>Vĩ tố dạng định ngữ</span>
            </div>
            <div class="entry"><span>Vĩ tố dạng trạng ngữ</span>
            </div>
            <div class="entry"><span>Vĩ tố dạng danh từ/danh ngữ</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="entry"><span>Nhóm định từ</span>
      <div class="branch">
        <div class="entry"><span>Định từ</span>          
        </div>
      </div>
    </div>
    <div class="entry"><span>Nhóm phó từ</span>
      <div class="branch">
        <div class="entry"><span>Phó từ</span>          
        </div>
      </div>
    </div>
    <div class="entry"><span>Nhóm cảm từ</span>
      <div class="branch">
        <div class="entry"><span>Cảm từ</span>          
        </div>
      </div>
    </div>
  </div>
</div>

<style>
#tree {
  display: inline-block;
  padding: 10px;
}

#tree * {
  box-sizing: border-box;
}

#tree .branch {
  padding: 5px 0 5px 20px;
}

#tree .branch:not(:first-child) {
  margin-left: 170px;
}

#tree .branch:not(:first-child):after {
  content: "";
  width: 20px;
  border-top: 1px solid #ccc;
  position: absolute;
  left: 150px;
  top: 50%;
  margin-top: 1px;
}

.entry {
  position: relative;
  min-height: 42px;
  display: block;
}

.entry:before {
  content: "";
  height: 100%;
  border-left: 1px solid #ccc;
  position: absolute;
  left: -20px;
}

.entry:first-child:after {
  height: 10px;
  border-radius: 10px 0 0 0;
}

.entry:first-child:before {
  width: 10px;
  height: 50%;
  top: 50%;
  margin-top: 1px;
  border-radius: 10px 0 0 0;
}

.entry:after {
  content: "";
  width: 20px;
  transition: border 0.5s;
  border-top: 1px solid #ccc;
  position: absolute;
  left: -20px;
  top: 50%;
  margin-top: 1px;
}

.entry:last-child:before {
  width: 10px;
  height: 50%;
  border-radius: 0 0 0 10px;
}
.entry:last-child:after {
  height: 10px;
  border-top: none;
  transition: border 0.5s;
  border-bottom: 1px solid #ccc;
  border-radius: 0 0 0 10px;
  margin-top: -9px;
}

.entry:only-child:after {
  width: 10px;
  height: 0px;
  margin-top: 1px;
  border-radius: 0px;
}

.entry:only-child:before {
  display: none;
}

.entry span {
  border: 1px solid #ccc;
  display: block;
  min-width: 150px;
  padding: 5px 10px;
  line-height: 20px;
  text-align: center;
  position: absolute;
  left: 0;
  top: 50%;
  margin-top: -15px;
  color: #666;
  font-family: arial, verdana, tahoma;
  font-size: 14px;
  display: inline-block;
  border-radius: 5px;
  transition: all 0.5s;
}

#tree .entry span:hover,
#tree .entry span:hover + .branch .entry span {
  background: #e6e6e6;
  color: #000;
  border-color: #a6a6a6;
}

#tree .entry span:hover + .branch .entry::after,
#tree .entry span:hover + .branch .entry::before,
#tree .entry span:hover + .branch::before,
#tree .entry span:hover + .branch .branch::before {
  border-color: #a6a6a6;
}
</style>

