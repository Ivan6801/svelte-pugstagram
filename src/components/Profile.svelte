<script>
  export let Name = 'IvanGlz';
</script>

<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://avatars.githubusercontent.com/u/60527338?v=4" alt="">
        </div>
        <div class="Profile-info">
            <h2>{Name}</h2>
            <span>{Name}</span>
        </div>
    </div>
</div>

<style>
    .Profile-content {
      display: flex;
      align-items: center;
    }
    .Profile-avatar img {
      width: 42px;
      height: 42px;
      border-radius: 50%;
    }
    .Profile-info {
      margin: 0 0 0 0.5em;
    }
    .Profile-info h2 {
      font-size: 14px;
      color: black;
      margin: 0;
      padding: 0;
    }
    .Profile-info span {
      font-size: 12px;
      font-weight: normal;
    }
  </style>