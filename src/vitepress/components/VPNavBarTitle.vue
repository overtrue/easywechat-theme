<template>
  <a class="VPNavBarTitle" href="/">
    <svg height="65%" viewBox="0 0 131 131" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
        <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
            <g>
                <g>
                    <g>
                        <polygon id="Rectangle-Copy-3" fill-opacity="0.882189764" fill="#5477F8" points="0.181818182 33 64 65 64 131 0 98.8181818"></polygon>
                        <polygon id="Rectangle" fill="#A4C4FA" opacity="0.6" points="64 64.9393382 126 32 126 98.0606618 64 131"></polygon>
                        <polygon id="Rectangle-Copy" fill="#F5F5F5" points="33 48.9393382 95 16 95 82.0606618 33 115"></polygon>
                        <polygon id="Rectangle-Copy-2" fill-opacity="0.882189764" fill="#5477F8" points="0.181818182 33.2422018 64 0 64 65.9394495 0 99"></polygon>
                    </g>
                </g>
            </g>
        </g>
    </svg>
    <span class="text">EasyWeChat</span>
  </a>
</template>

<style scoped>
.VPNavBarTitle {
  display: flex;
  align-items: center;
  padding-top: 1px;
  height: var(--vt-nav-height);
  transition: opacity 0.25s;
}

.VPNavBarTitle:hover {
  opacity: 0.6;
}

.logo {
  position: relative;
}

.logo + .text {
  padding-left: 8px;
}

.text {
  font-size: 16px;
  font-weight: 500;
  margin-left: 0.5rem;
}
</style>
