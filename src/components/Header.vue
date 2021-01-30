 <template>
    <div class="header-wrapper">
        <router-link to="/" class="header-logo">
            <svg 
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                width="70px" height="28px">
                <image  x="0px" y="0px" width="70px" height="28px"  xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAcCAMAAADr5TknAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAA9lBMVEX////+/f719fX9/Pzv7+/l5ubr6+v4+PhgYGBAQEBCQ0bExcf7+/uEg4QvLy9NTU7y8vL39/coJygAAAASEhK4urn6+vpvb3Dx8fE0NDUGBgYgICC/wMCQkZJoZ2j29vf7/f7M1/i/zvbn7Pyur7Dk5OTs7Ox1dXaLi4vo6egaGhrV2NmnqKnu7u7h4eGfn59/gICVmZzPz8/x9f9chORLb9+1xvX+///Z2dlaWlsMDAy1tbVQfOKkpKRWVVX09PT+//59fHzT1NU6OjrJzM14eX7//v8TExMNDQ0HBwff3997mer2+v6Iouvs8Pzd5PtujueovvN035MRAAAAAWJLR0QAiAUdSAAAAAd0SU1FB+UBHBQhJXFGKw4AAAH5SURBVDjLrZNpd5pAFIbvOIEo7gy4IJhELQIdQ7Q1LsHWEGsX7fb//0zvCBp6qqe15P0yw8zlOc9sAH+GZBKh5EKSZALn5zKbO0TJF4qlUrnyH5iqyg7R9FqdsVLjTARB/cumpmmGYGhay6RWWWlfJaZFc/gk8cj1zU2nC0DNXu+VrVt9R6+B7LoSOnivXdfNYF+ySUPnvcEtd4p6tWL6d8MR/m3zYh+z6795Ox7fT6CgMKY0hYJhUaTTPmJk7MhNVVXLjWmJsZlY7LytiCrPhIESL9x7IIgJxvcAhfJuRFSoUhIjaUzsjcBE00bUzOhCEDxvzti79xFmucN4j0OOjRYmMXZW3WNyzmKGjKy1aKF6RlSMKjauXpWTNk+4kT5iRkkMvajvMRaBhcG0PEAOMVdY0TLDsI2NnLR5qh7BQO0ZA8ARs3rGGJonjrT1u83ZmDhpbTzLF+E0hc0HcdTTcGX2puSYTXgCM4wx6wiDpewj5tNnh5y0qR+1OZyUoVSl+PoZc+tgQ0zOTbzUXzh/EM+ZjLBT2L2bFec6qeic30bTAwD8yFOQ/LtHx/J7pgx7m9NZrk+/Y0r3jzS2SZu/2vwzJthsU2O2myAIvn5Li5l833FS+yy7P17EByJOWp/Jy/lsxkHQSb09191N8DP9qeM+d7brFP//Ah/zZ3wLOrHPAAAAAElFTkSuQmCC" />
            </svg>
        </router-link>

        <router-link to="/" exact active-class="acrive">
            <a href="#" class="header-link">
                <p>Dashboard</p>
            </a>
        </router-link> 

        <router-link to="/calendar" active-class="active">
            <a href="#" class="header-link">
                <p>Calendar</p>
            </a>
            </router-link>

        <form class="header-search-form">
            <input class="search" type="search" placeholder="Search">
            <button>
                <i class="fas fa-search"></i>
            </button>
        </form>

        <button>
            <i class="far fa-clock"></i>
        </button>

        <div class="accaunt">
            <img src="../assets/accaunt.jpg" alt="accaunt image">
            <button>
                <i class="fas fa-angle-down"></i>
            </button>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>