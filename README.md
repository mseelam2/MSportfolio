<script>
  const content = {
    about: `
      <h2>About Me</h2>
      <p>Hi, I’m <strong>Maddy Rao</strong>—a PMO & Agile Strategist who started my journey in India and has spent the last decade turning unknowns into opportunities in the USA. With a background in seat-design engineering at Whirlpool and leading cross-functional teams, I thrive on building processes that empower people and drive results.</p>
      <p>Outside of work, I’m a volunteer leader with SWE and PMI—mentoring aspiring project managers, organizing workshops, and studying for my PMP, PMI-ACP, and RMP certifications. I believe that growth isn’t linear: sometimes it’s a crawl, sometimes a leap, but it’s always an adventure.</p>
    `,
    projects: `
      <h2>Projects</h2>
      <ul>
        <li><strong>Smart Kitchen Integration:</strong> Enhanced user experience by integrating IoT devices into Whirlpool appliances.</li>
        <li><strong>OEM Seat Design:</strong> Delivered 7+ seat models over 4 years for a major automotive brand, streamlining design and supplier collaboration.</li>
        <li><strong>Volunteer PMO Toolkit:</strong> Built templates and guidelines to help nonprofit chapters adopt PMO practices efficiently.</li>
      </ul>
    `,
    resume: `
      <h2>Resume</h2>
      <p><strong>Experience</strong></p>
      <ul>
        <li><strong>Project Leader, Whirlpool Corporation</strong> (2018–2021)<br>
          • Led PMO initiatives for smart-kitchen integration, improving time-to-market by 20%<br>
          • Implemented Agile workflows across 3 global teams</li>
        <li><strong>Seat Design Engineer, OEM Automotive</strong> (2014–2018)<br>
          • Delivered 7+ seat models for a major auto brand, managing end-to-end design and supplier coordination<br>
          • Reduced prototype iteration time by 30% through process optimization</li>
      </ul>
      <p><strong>Education & Certifications</strong></p>
      <ul>
        <li>M.S. in Mechanical Engineering, [Your University]</li>
        <li>PMP® (in progress), PMI-ACP® (in progress), RMP® (in progress)</li>
        <li>B.Tech in Mechanical Engineering, [Your College]</li>
      </ul>
      <p><strong>Skills</strong>: Agile & Waterfall PMO • Process Improvement • Stakeholder Management • Cross-functional Leadership • IoT & Product Integration • CAD (Creo, SolidWorks)</p>
      <p><strong>Volunteer</strong>: SWE Social Chair • PMI Chapter Mentor • Workshop Organizer</p>
      <p><a href="Mary Seelam Resume May 2024.pdf" target="_blank">Download Full Resume (PDF)</a></p>
    `,
    contact: `
      <h2>Contact</h2>
      <p>Email: your.email@example.com</p>
      <p>LinkedIn: <a href="#" target="_blank">linkedin.com/in/yourname</a></p>
    `
  };

  function showSection(section) {
    document.getElementById("main-content").innerHTML = content[section];
  }
</script>
