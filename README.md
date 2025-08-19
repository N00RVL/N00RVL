<pre align="left"><code>███╗   ██╗ ██████╗  ██████╗ ██████╗ ██╗   ██╗██╗     
████╗  ██║██╔═══██╗██╔═══██╗██╔══██╗██║   ██║██║     
██╔██╗ ██║██║   ██║██║   ██║██████╔╝██║   ██║██║     
██║╚██╗██║██║   ██║██║   ██║██╔══██╗██║   ██║██║     
██║ ╚████║╚██████╔╝╚██████╔╝██║  ██║╚██████╔╝███████╗
╚═╝  ╚═══╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚══════╝

</code></pre>

<pre style="background:#0d1117;padding:12px 14px;border-radius:6px;line-height:1.25;overflow:auto;font-size:13px">
<span style="color:#8b949e"># 🌐︎ Website: </span><a href="https://bitwa.re" style="color:#ffffff;text-decoration:none">https://bitwa.re</a>
<span style="color:#8b949e"># ✉️ Email:  </span><a href="mailto:noorul@bitwa.re" style="color:#ffffff;text-decoration:none">noorul@bitwa.re</a>
</pre>

```python

STACK = [
    ("Automation ",   ["n8n"]),
    ("Languages",     ["C", "C++", "C#", "Java", "Python", "JS", "TS", "R"]),
    ("Frontend ",     ["Next.js", "React", "Tailwind CSS"]),
    ("Frameworks",    ["Node.js", "FastAPI", ".NET"]),
    ("Databases ",    ["PostgreSQL"]),
    ("Cloud",         ["GCP", "AWS", "Kubernetes"]),
    ("Mobile Dev",    ["Flutter","Swift"]),
]


def print_section():
    print("N00RVL :: PROFILE\n")
    print("Stack:")
    for name, items in STACK:
        print(f"- {name}:")
        for i, val in enumerate(items):
            suffix = "," if i + 1 < len(items) else ""
            print(f"    {val}{suffix}")

if __name__ == "__main__":
    print_section()
```

![](assets/scrf.svg)
